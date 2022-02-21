<template>
    <div class="features">
        <div class="onePic">
            <div class="textOne">
                LEARN MORE ABOUT
            </div>
        </div>
        <div class="twoPic">
            <div class="preTextFeatures">
                FEATURES
            </div>
            <div class="FeaturesHead">
                Emergency care for children
            </div>
            <div class="textFeatures">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum 
            </div>
        </div>
        <div class="threePic">
            <div class="preTextFeatures">
                FEATURES
            </div>
            <div class="FeaturesHead">
                Professional surgeons
            </div>
            <div class="textFeatures">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum 
            </div>
        </div>
        <div class="fourPic">
            
        </div>
    </div>
</template>

<style lang="sass">
    .features
      position: relative
      height: 950px
      width: 100%
      max-width: 1920px
      margin: auto
    .onePic
      width: 50%
      height: 50%
      top: 0
      left: 0
      position: absolute
      background-image: url("../assets/images/hover.png")

    .twoPic
      left: 0
      bottom: 0
      background-color: #6bc2f1
      width: 50%
      height: 50%
      position: absolute
    .threePic
      right: 0
      top: 0
      background-color: #6bc2f1
      width: 50%
      height: 50%
      position: absolute
    .fourPic
      bottom: 0
      right: 0
      width: 50%
      height: 50%
      position: absolute
      background-image: url("../assets/images/replace-image1.png")
    .textOne
      color: white
      font-family: 'Roboto', sans-serif
      font-size: 26pt
      text-align: center
      margin-top: 242px
    .preTextFeatures
      color: white
      font-family: 'Roboto', sans-serif
      font-size: 19pt
      text-align: center
      margin-top: 100px
      margin-bottom: 10px
    .FeaturesHead
      color: white
      font-family: 'Roboto', sans-serif
      font-size: 36pt
      text-align: center
      margin-bottom: 30px
    .textFeatures
      color: white
      font-family: 'Roboto', sans-serif
      font-size: 18pt
      text-align: center
      margin: auto
      line-height: 40px

  @media (max-width: 1024px) 
    .features
      height: 540px
      max-width: 1024px
    .onePic
      background-size: 450px 360px
    .fourPic
      background-size: 520px 290px
    .textOne
      font-size: 16pt
      text-align: center
      margin-top: 120px
    .preTextFeatures
      font-size: 9pt
      text-align: center
      margin-top: 50px
      margin-bottom: 7px
    .FeaturesHead
      font-size: 13pt
      text-align: center
      margin-bottom: 22px
    .textFeatures
      font-size: 9pt
      text-align: center
      margin: auto
      line-height: 30px
  
  @media (max-width: 800px) 
    .features
      height: 490px
      max-width: 800px
    .onePic
      background-size: 400px 300px
    .fourPic
      background-size: 400px 250px
    .textOne
      font-size: 11pt
      text-align: center
      margin-top: 120px
    .preTextFeatures
      font-size: 7pt
      text-align: center
      margin-top: 50px
      margin-bottom: 5px
    .FeaturesHead
      font-size: 14pt
      text-align: center
      margin-bottom: 15px
    .textFeatures
      font-size: 7pt
      text-align: center
      margin: auto
      line-height: 20px

  @media (max-width: 400px) 
    .features
      height: 245px
      max-width: 400px
    .onePic
      background-size: 200px 150px
    .fourPic
      background-size: 200px 125px
    .textOne
      font-size: 5pt
      text-align: center
      margin-top: 60px
    .preTextFeatures
      font-size: 4pt
      text-align: center
      margin-top: 25px
      margin-bottom: 3px
    .FeaturesHead
      font-size: 7pt
      text-align: center
      margin-bottom: 6px
    .textFeatures
      font-size: 4pt
      text-align: center
      margin: auto
      line-height: 10px
</style>