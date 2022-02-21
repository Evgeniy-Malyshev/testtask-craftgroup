<template>
<div id="formHyp" class="mainform">
  <div class="form">
    <div class="formContainer">
        <p class="formHeader">Contact us</p>
        <div class="name">
            <input type="text" class="formInput" placeholder="Name"
            v-model="name"
            @blur="$v.name.$touch()" 
            :class="{isinvalid: $v.name.$error, isNOTinvalid: !$v.name.$error && this.name != ''}"
            />
            
            <div v-if="!$v.name.required && $v.name.$dirty" class="necessarily">
                {{nonRequired}}
            </div>

            <div v-if="!$v.name.alpha" class="necessarily">
                {{nonAlpha}}
            </div>

            <div v-if="!$v.name.minLength" class="necessarily">
                Name too short
            </div>

            <div v-if="!$v.name.maxLength" class="necessarily">
                Name too long
            </div>

        </div>


        <div class="email">
            <input type="text" class="formInput" placeholder="Email"
            v-model="email"
            @blur="$v.email.$touch()" 
            :class="{isinvalid: $v.email.$error, isNOTinvalid: !$v.email.$error && this.name != ''}"
            />
            
            <div v-if="!$v.email.required && $v.email.$dirty" class="necessarily">
                {{nonRequired}}
            </div>

            <div v-if="!$v.email.email" class="necessarily">
                not an email address
            </div>
        </div>

        <div class="subject">
            <input type="text" class="formInput" placeholder="Subject"/>
        </div>
        <div class="massage">
            <input type="text" class="formInputMassage" placeholder="Your Massage"/>
        </div>
        <button class="Btn" type="button">SUBMIT</button>
    </div>
  </div>
</div>
</template>

<script>

import { required, helpers, minLength, maxLength, email} from 'vuelidate/lib/validators'
const alpha = helpers.regex('alpha', /^[a-zA-Zа-яёА-ЯЁ]*$/)

export default {
  data() {
    return{
      nonRequired: 'Required field',
      nonAlpha: 'the use of numbers and symbols is prohibited',
      name: '',
      email: '',
      subject: '',
      yourmassage: ''
    }
  },
  validations: {
    name: {
      required,
      alpha,
      minLength: minLength(2),
      maxLength: maxLength(24)
    },
    email: {
      required,
      email
    }
  }
}
</script>


<style lang="sass">
.form
  width: 100%
  margin: auto

.formContainer
  position: relative
  max-width: 420px
  margin: 0 auto 0
  
  input
    font-family: "Roboto", sans-serif
    outline: 0
    background: white
    width: 100%
    border: 1px solid grey
    margin-top: 10px 
    margin-bottom: 2px
    padding: 10px
    font-size: 14px

    &:hover, &:active, &:focus
     outline: 1px solid #63a1db
     border: 1px solid #63a1db
     background: white


  .isinvalid, .isPhoneInvalid
    outline: 1px solid #fa756b
    border: 1px solid #fa756b
    background: #faccc5

  .isNOTinvalid
    outline: 1px solid #50b54e
    border: 1px solid #50b54e
    background: #ccfcce

  .necessarily
    color: red
    font-size: 13px
    font-family: "Roboto", sans-serif
  
  .Btn, .BtnBack
    padding: 10px
    font-size: 16px
    width: 40%
    display: block
    margin: auto
    margin-top: 20px
    border: 1px solid #6bc2f1
    outline: 0
    background: white
    border-radius: 5px
    color: #6bc2f1
    margin-bottom: 90px

    &:hover, &:active, &:focus
      background: white
      outline: 0
      border: 1px solid #6bc2f1
    &:disabled
        background: #909bd1

  .BtnBack 
    background: #a8a7a7
    &:hover, &:active, &:focus
      background: #918e8e
  option
    padding: 8px
    float: left
    background-color: #fff
    font-family: "Roboto", sans-serif
    color: #2d2d2e
    outline: 1px solid #2d2d2e

  .formHeader
    font-family: "Roboto", sans-serif
    font-size: 36px
    color: #413d4b
    text-align: center
    margin-top: 150px
  .name, .subject, .email
    margin-bottom: 15px
  .massage
    margin-bottom: 25px
    height: 200px


@media (max-width: 800px) 
  .formContainer
    max-width: 210px
  
  input
    width: 100%
    margin-top: 5px 
    margin-bottom: 1px
    padding: 5px
    font-size: 7px

  .necessarily
    color: red
    font-size: 7px
    font-family: "Roboto", sans-serif
  
  .Btn, .BtnBack
    padding: 5px
    font-size: 8px
    width: 40%
    margin-top: 10px
    border-radius: 5px
    margin-bottom: 45px

  option
    padding: 4px

  .formHeader
    font-size: 18px
    margin-top: 75px
  .name, .subject, .email
    margin-bottom: 7px
  .massage
    margin-bottom: 11px
    height: 100px
</style>