<template>
<div class="colorphoto">
  <div class="portfolio container">
        <div id="#photos" class="photos container">
            <a href="#img1"><img class="imga" src="../assets/Portfolio/replace imageA.png" alt=""></a>
            <div id="img1" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageA.png" alt="">
            </div>
            <a href="#img2"><img class="imgc" src="../assets/Portfolio/replace imageC.png" alt=""></a>
            <div id="img2" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageC.png" alt="">
            </div>
            <a href="#img3"><img class="imge" src="../assets/Portfolio/replace imageE.png" alt=""></a>
            <div id="img3" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageE.png" alt="">
            </div>
            <br/>
            <a href="#img4"><img class="imgb" src="../assets/Portfolio/replace imageB.png" alt=""></a>
            <div id="img4" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageB.png" alt="">
            </div>
            <a href="#img5"><img class="imgd" src="../assets/Portfolio/replace imageD.png" alt=""></a>
            <div id="img5" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageD.png" alt="">
            </div>
            <a href="#img6"><img class="imga" src="../assets/Portfolio/replace imageF.png" alt=""></a>
            <div id="img6" class="popup">
            <a href="#photos" class="close">X</a>
            <img class="full-img" src="../assets/Portfolio/replace imageF.png" alt="">
            </div>
        </div>
    </div>
</div>
</template>

<style lang="sass" scoped>
    .colorphoto
      background-color: #f1f1f1
    .portfolio
      background-color: #f1f1f1
      width: 100%
      max-height: 750px
    .photos
      margin-left: 30px
    img 
      display: inline-block
      margin-right: 20px
      margin-bottom: 20px
    
    .imga
      
      &:hover, &:active, &:focus
        -webkit-transform: scale(1.2)
        -ms-transform: scale(1.2)
        transform: scale(1.2)

    .imgc
      
      &:hover, &:active, &:focus
        opacity: 1
        opacity: 0.6

    .imge
      
      &:hover, &:active, &:focus
        -webkit-transform: scale(0.7)
        -ms-transform: scale(0.7)
        transform: scale(0.7)


    .imgb
      
      &:hover, &:active, &:focus
        -webkit-transform: rotateZ(20deg)
        -ms-transform: rotateZ(20deg)
        transform: rotateZ(20deg)


    .imgd
      
      &:hover, &:active, &:focus
        border-radius: 70%

    .imga
      
      &:hover, &:active, &:focus
        -webkit-transform: scale(1.2)
        -ms-transform: scale(1.2)
        transform: scale(1.2)

    .container
      max-width: 1300px
    .photos
      padding-top: 60px
      padding-bottom: 60px
    .bpic
      padding-top: 30px
    .popup:not(:target) 
      display: none
    .popup:target 
      display: block
      position: fixed
      top: 0
      left: 0
      bottom: 0
      right: 0
      background: rgba(0,0,0,0.9)
    .full-img 
      position: absolute
      top: 50%
      left: 50%
      width: 80%
      z-index: 10
      transform: translate(-50%, -50%)
    .close
      position: absolute
      top: 20px
      right: 20px
      font-size: 30px
      text-decoration: none
      color: red

@media (max-width: 1024px) 
  img 
    display: inline-block
    margin-right: -20px
    margin-bottom: 32px
    width: 220px
    margin-left: 70px
@media (max-width: 800px) 
  img 
    display: inline-block
    margin-right: 10px
    margin-bottom: 10px
    width: 160px
@media (max-width: 400px) 
  img 
    display: inline-block
    margin-right: 5px
    margin-bottom: 5px
    width: 70px
</style>
