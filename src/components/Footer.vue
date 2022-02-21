<template>
    <div class="footer">
        <div class="container">
            <div class="colomns">
                <div class="colomn colomnone">
                    <div class="colomnHead">
                        Medical
                    </div>
                    <div class="colomnText">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                    </div>
                    <div class="colomnText">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate 
                    </div>
                </div>
                <div class="colomn colomntwo">
                    <div class="colomnHead">
                        New York
                    </div>
                    <div class="colomnText">
                        709 Honey Creek Dr. <br> New York <br> NY 10028
                    </div>
                    <div class="colomnText">
                        1-888-299-2000 <br> yourmail@ompany.com
                    </div>
                </div>
                <div class="colomn colomntree">
                    <div class="colomnHead">
                        London
                    </div>
                    <div class="colomnText">
                        4851 Willow Greene Drive <br> Montgomery <br> AL 36109
                    </div>
                    <div class="colomnText">
                        1-888-299-2000 <br> yourmail@ompany.com
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="sass">
    .footer
      background-color: #072135
      max-width: 1920px
      width: 100%
      margin: auto
      height: 458px
    .colomn
      float: left
      margin-top: 130px
      color: white
      font-family: 'Roboto', sans-serif
    .colomnHead
      font-size: 15pt
      margin-bottom: 42px
    .colomnText
      color: #b5bdc3
      margin-top: 39px
      font-size: 10pt
    .colomnone
      width: 470px
      margin-right: 150px
    .colomntwo
      width: 170px
      margin-right: 150px


@media (max-width: 1024px) 
  .footer
      max-width: 1024px
      height: 244px
  .colomn
      float: left
      margin-top: 65px
  .colomnHead
      font-size: 7pt
      margin-bottom: 20px
  .colomnText
      color: #b5bdc3
      margin-top: 19px
      font-size: 5pt
  .colomnone
      width: 235px
      margin-right: 75px
  .colomntwo
      width: 85px
      margin-right: 75px

@media (max-width: 800px) 
  .footer
      max-width: 800px
      height: 244px
  .colomn
      float: left
      margin-top: 65px
  .colomnHead
      font-size: 7pt
      margin-bottom: 20px
  .colomnText
      color: #b5bdc3
      margin-top: 19px
      font-size: 5pt
  .colomnone
      width: 235px
      margin-right: 75px
  .colomntwo
      width: 85px
      margin-right: 75px

@media (max-width: 400px) 
  .footer
      max-width: 400px
      height: 122px
  .colomn
      float: left
      margin-top: 32px
      margin-left: 10px
  .colomnHead
      font-size: 3pt
      margin-bottom: 10px
  .colomnText
      color: #b5bdc3
      margin-top: 8px
      font-size: 3pt
  .colomnone
      width: 115px
      margin-right: 35px
  .colomntwo
      width: 42px
      margin-right: 35px
</style>