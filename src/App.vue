<template>
  <div id="app">
    <Header/>
    <About id="about"/>
    <Works id="works"/>
    <Skills id="skills"/>
    <Contact id="contact"/>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import About from '@/components/About.vue'
import Skills from '@/components/Skills.vue'
import Contact from '@/components/Contact.vue'
import Footer from '@/components/Footer.vue'
import Works from '@/components/Works.vue'

export default {
  name: 'App',
  components: { 
    Header,
    About,
    Works,
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
  background: #151515 url('../src/assets/images/image02.jpg') no-repeat fixed left bottom;
  background-size: cover;
  color: #fff;
  text-align: center;
  font-size: 1.4rem;
  font-family: Raleway, "Hiragino Kaku Gothic ProN", Meiryo, sans-serif;
}
.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
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
@media (max-width: 768px) {
  body {
    font-size: 1.3rem;
  }
  .heading {
    margin-top: 20px;
    font-size: 2.5rem;
  }
}
</style>
