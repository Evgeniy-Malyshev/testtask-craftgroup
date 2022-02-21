<template>
  <div id="app">
    <div class="header">
      <div class="progress-container">
        <div class="progress-bar" id="myBar"></div>
      </div>  
    </div>
    <Head/>
    <About/>
    <Feature/>
    <Portfolio v-bind:showPic="showPic"/>
    <Form/>
    <Footer/>
  </div>
</template>

<script>

import Head from './components/Head.vue'
import About from './components/About.vue'
import Feature from './components/Feature.vue'
import Portfolio from './components/Portfolio.vue'
import Form from './components/Form.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Head,
    About,
    Feature,
    Portfolio,
    Form,
    Footer
  }
}

window.onscroll = function() {lineScroll()};
function lineScroll() {
  let winScroll = document.body.scrollTop || document.documentElement.scrollTop
  let height = document.documentElement.scrollHeight - document.documentElement.clientHeight
  let scrolled = (winScroll / height) * 100
  document.getElementById("myBar").style.width = scrolled + "%"
}
</script>

<style lang="sass" scoped>
.header 
  position: fixed
  top: 0
  z-index: 1
  width: 100%
  background-color: #f1f1f1
.progress-container 
  width: 100%
  height: 8px
  background: #ccc
.progress-bar 
  height: 8px
  background: #0776A0
  width: 0%
</style>