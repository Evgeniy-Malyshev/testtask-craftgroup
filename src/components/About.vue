<template>
    <div>
        <div class="About">
            <div class="container">
                <div class="textBlock">
                    <div class="textBlue">
                        WELCOME TO CLINIC
                    </div>
                    <div class="head">
                        Why you should choose us ?
                    </div>
                    <div class="textAbout">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehen-
                    </div>
                    <form action="#formHyp">
                      <button class="buttonGetStartedNowBlue">Get started now</button>
                    </form>
                    <div class="img">
                        <img src="../assets/images/replace-image.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="sass">
    .textBlock
      position: relative
    .textBlue
      font-size: 19pt
      font-family: 'Roboto', sans-serif
      color: #6bc2f1
      margin-top: 270px
      margin-bottom: 50px
    .head
      font-size: 36pt
      font-family: 'Roboto', sans-serif
      margin-bottom: 25px
    .textAbout
      font-size: 18pt
      font-family: 'Roboto', sans-serif
      color: #5f5f5f
      width: 735px
    .buttonGetStartedNowBlue
      color: white
      font-family: 'Roboto', sans-serif
      font-weight: 700
      font-size: 12pt
      background-color: #6bc2f1
      border: 0
      padding: 20px 43px
      margin-top: 67px
      margin-bottom: 266px

      &:hover, &:active, &:focus
        background: #148fd2
    .img
      position: absolute
      right: 0
      bottom: 100px
  
  
  @media (max-width: 1024px) 
    .container
      max-width: 900px
    img
      width: 300px
    .img
      top: -50px
    .textBlue
      font-size: 10pt
      margin-top: 120px
      margin-bottom: 35px
    .head
      font-size: 20pt
      margin-bottom: 17px
    .textAbout
      font-size: 12pt
      width: 500px
    .buttonGetStartedNowBlue
      font-weight: 700
      font-size: 10pt
      padding: 15px 27px
      margin-top: 45px
      margin-bottom: 162px
  
  @media (max-width: 800px) 
    .container
      max-width: 700px
    img
      width: 250px
    .img
      top: -70px
    .textBlue
      font-size: 8pt
      margin-top: 100px
      margin-bottom: 25px
    .head
      font-size: 16pt
      margin-bottom: 13px
    .textAbout
      font-size: 9pt
      width: 320px
    .buttonGetStartedNowBlue
      font-weight: 700
      font-size: 6pt
      padding: 10px 20px
      margin-top: 33px
      margin-bottom: 122px
  
  @media (max-width: 400px) 
    .container
      max-width: 350px
    img
      width: 125px
    .img
      top: -35px
    .textBlue
      font-size: 4pt
      margin-top: 50px
      margin-bottom: 12px
    .head
      font-size: 8pt
      margin-bottom: 7px
    .textAbout
      font-size: 4pt
      width: 160px
    .buttonGetStartedNowBlue
      font-size: 3pt
      padding: 5px 10px
      margin-top: 15px
      margin-bottom: 60px
</style>
