<template>
  <header class="header">
    <h1 class="site-title">Kazuki's portfolio</h1>
    <p class="site-title-sub">Web Engineer</p>
    <div class="buttons">
      <a class="button" href="#about">About</a>
      <a class="button" href="#skills">Skills</a>
      <a class="button" href="#contact">Contact</a>
    </div>
  </header>
</template>

<script>
</script>

<style>
.header {
  padding: 170px 80px;
}
.site-title {
  margin: 50px 0 40px;
  font-size: 7.6rem;
}
.site-title-sub {
  margin: 0 0 30px;
  letter-spacing: 1px;
  font-size: 2.2rem;
}
.site-title-sub::before, .site-title-sub::after {
  content: '';
  display: inline-block;
  width: 140px;
  height: 2px;
  margin: 0 30px;
  background-color: #fff;
  vertical-align: middle;
}
.buttons {
  padding-top: 80px;
}
</style>
