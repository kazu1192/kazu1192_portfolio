<template>
  <div id="app">
    <Header/>
    <About/>
    <section class="skills" id="skills">
    </section>
    <section class="contact" id="contact">
    </section>
    <footer class="footer">
    </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'

export default {
  components: { 
    Header,
    About
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
</style>
