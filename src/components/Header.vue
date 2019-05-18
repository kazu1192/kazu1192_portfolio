<template>
  <div class="flex-center">
    <div class="header">
      <p class="site-title-sub">Web Engineer</p>
      <h1 class="site-title">KAZUKI'S PORTFOLIO</h1>
      <div class="buttons">
        <a class="button" href="#about">About</a>
        <a class="button" href="#skills">Skills</a>
        <a class="button" href="#contact">Contact</a>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.site-title-sub {
  margin: 0 0 30px;
  letter-spacing: 1px;
  font-size: 2.2rem;
}
.site-title-sub::before, 
.site-title-sub::after {
  content: '';
  display: inline-block;
  width: 140px;
  height: 2px;
  margin: 0 30px;
  background-color: #fff;
  vertical-align: middle;
}
.site-title {
  margin: 50px 0 40px;
  font-size: 7.6rem;
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
@media (max-width: 768px) {
  .header {
    padding-top: 60px;
  }
  .site-title {
    margin-top: 35px;
    font-size: 5rem;
  }
  .site-title-sub {
    font-size: 1.7rem;
  }
  .site-title-sub::before, 
  .site-title-sub::after {
    display: block;
    width: 80%;
    margin: 10px auto;
  }
  .buttons .button {
    width: 30%;
    font-size: 1.5rem;
    margin: auto;
    padding: 0;
  }
}
</style>
