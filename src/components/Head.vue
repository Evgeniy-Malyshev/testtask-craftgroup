<template>
    <div>
        <div class="main">
            <div class="header">
                <div class="container">
                    <div class="logo">
                        MEDICAL
                    </div>
                    <div class="menu">
                        <ul>
                            <li><a href="#">Home</a></li>
                            <li><a href="#">About us</a></li>
                            <li><a href="#">Services</a></li>
                            <li><a href="#">Portfolio</a></li>
                            <li><a href="#">Blog</a></li>
                            <li><a href="#">Contact</a></li>
                        </ul>
                    </div>
                      <form action="#formHyp">
                      <button class="buttonGetStarted">Get started</button>
                      </form>
                </div>
            </div>
            <div class="container">
                <div class="titlehead">
                    The best doctors <br> in <b>Medicine!</b>
                </div>
                <div class="titletext">
                    in the world of modern medicine!
                </div>
                <div class="text">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed <br> do eiusmod tempor incididunt ut labore et dolore magna <br> aliqua. Ut enim ad minim veniam, quis nostrud exercitation 
                </div>

                <form action="#formHyp">
                      <button class="buttonGetStartedNow">Get started now</button>
                </form>
            </div>
        </div>
    </div>
</template>

<script>


</script>

<style lang="sass">
    body
      margin: 0
    ul
      margin: 0
      position: absolute
      bottom: 0
      left: 20%
      padding: 0
    li 
      list-style-type: none
      float: left
      padding-top: 33px
      padding-bottom: 35px
      margin: 0
    a
      color: black
      text-decoration: none
      font-family: 'Roboto', sans-serif
      font-weight: 700
      margin-right: 20px
    .main
      position: relative
      max-width: 1920px
      margin: auto
      background-image: url("../assets/images/bg-header-replace.png")
      background-repeat: no-repeat
    .container
      position: relative
      max-width: 1170px
      margin: auto
      
    .logo
      font-family: 'Roboto', sans-serif
      font-weight: 700
      font-size: 24pt
      padding-top: 29px
      padding-bottom: 31px
    .logo:first-letter
      color: #6bc2f1
    .header
      background-color: #fff
      opacity: 0.8
      z-index: -1
      width: 100%
    .menu
      left: 20%
    .buttonGetStarted
      color: white
      font-family: 'Roboto', sans-serif
      font-weight: 700
      font-size: 12pt
      background-color: #6bc2f1
      border: 0
      border-radius: 30
      padding: 20px 30px
      position: absolute
      right: 0
      top: 15px
        
      &:hover, &:active, &:focus
        background: #148fd2
        

    .titlehead 
      font-size: 70pt
      font-family: 'Roboto', sans-serif
      color: white
      margin-top: 200px
    .titletext
      font-size: 26pt
      font-family: 'Roboto', sans-serif
      color: white
    .text
      font-size: 18pt
      font-family: 'Roboto', sans-serif
      color: white
      margin-top: 58px
    .buttonGetStartedNow
      color: #061b46
      font-family: 'Roboto', sans-serif
      font-weight: 700
      font-size: 12pt
      background-color: white
      border: 0
      padding: 20px 43px
      margin-top: 67px
      margin-bottom: 115px

      &:hover, &:active, &:focus
        background: #5cbcf0

  @media (max-width: 1024px) 
    .logo
      font-size: 12pt
      padding-top: 14px
      padding-bottom: 14px
    .container
      max-width: 700px
    a
      font-size: 8pt
      margin-right: 13px
    li 
      padding-bottom: 15px
    .buttonGetStarted
      padding: 10px 20px
      font-size: 8pt
      top: 7px
    .main
      background-size: 1000px
    .titlehead
      font-size: 35pt
      margin-top: 100px
    .titletext
      font-size: 13pt
    .text
      font-size: 9pt
    .buttonGetStartedNow
      padding: 10px 20px
      font-size: 8pt
      top: 7px
      margin-bottom: 20px
      margin-top: 30px
  
  @media (max-width: 800px) 
    .logo
      font-size: 12pt
      padding-top: 14px
      padding-bottom: 14px
    .container
      max-width: 700px
    a
      font-size: 8pt
      margin-right: 13px
    li 
      padding-bottom: 15px
    .buttonGetStarted
      padding: 10px 20px
      font-size: 8pt
      top: 7px
    .main
      background-size: 1000px
    .titlehead
      font-size: 35pt
      margin-top: 100px
    .titletext
      font-size: 13pt
    .text
      font-size: 9pt
    .buttonGetStartedNow
      padding: 10px 20px
      font-size: 8pt
      top: 7px
      margin-bottom: 20px
      margin-top: 30px

  @media (max-width: 400px) 
    .logo
      font-size: 6pt
      padding-top: 7px
      padding-bottom: 7px
    .container
      max-width: 400px
    a
      font-size: 4pt
      margin-right: 6px
    li 
      padding-bottom: 7px
    .buttonGetStarted
      padding: 5px 10px
      font-size: 4pt
      top: 3px
    .main
      background-size: 500px
    .titlehead
      font-size: 17pt
      margin-top: 50px
    .titletext
      font-size: 7pt
    .text
      font-size: 4pt
      margin-top: 10px
    .buttonGetStartedNow
      padding: 5px 10px
      font-size: 4pt
      top: 3px
      margin-bottom: 10px
      margin-top: 10px
</style>
