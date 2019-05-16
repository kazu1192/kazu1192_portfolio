<template>
  <div id="app">
    <Header/>
    <About/>
    <Skills/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  components: { 
    Header,
    About,
    Skills,
    Contact,
    Footer
  }
};
</script>

<style>
html {
  font-size: 62.5%;
}
*, *::before, *::after {
  box-sizing: border-box;
}
body {
  background: #151515;
  color: #fff;
  text-align: center;
  font-size: 1.4rem;
  font-family: Raleway, "Hiragino Kaku Gothic ProN", Meiryo, sans-serif;
}
.heading {
  position: relative;
  display: inline-block;
  margin: 30px 0 15px;
  padding-bottom: 15px;
  letter-spacing: 2px;
  font-size: 4rem;
}
.heading::before, .heading::after {
  content: '';
  position: absolute;
  right: 0;
  bottom: 0; 
  left: 0;
  border-bottom: 1px solid #999;
}
.heading::before {
  bottom: 5px;
}
.button {
  display: inline-block;
  width: 200px;
  padding: 20px;
  border-radius: 4px;
  color: #fff;
  text-decoration: none;
  letter-spacing: 1px;
  font-size: 2.2rem;
}
.button:hover {
  opacity: 0.9;
}
.buttons .button {
  margin: 10px;
}
</style>
