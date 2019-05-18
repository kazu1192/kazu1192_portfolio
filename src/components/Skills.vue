<template>
  <div class="flex-center back-dark">
    <div class="skills">
      <h2 class="heading">SKILLS</h2>
      <p class="skills-text">使用可能な言語スキル</p>
      <div class="skills-wrapper">
        <img src="@/assets/images/svg/ruby.svg" alt="Ruby">
        <img src="@/assets/images/svg/rails.svg" alt="Ruby on Rails">
        <img src="@/assets/images/svg/java.svg" alt="Java">
        <img src="@/assets/images/svg/struts.svg" alt="Struts">
        <img src="@/assets/images/svg/spring.svg" alt="Spring">
        <img src="@/assets/images/svg/android-icon.svg" alt="Android">
        <img src="@/assets/images/svg/php.svg" alt="PHP">
        <img src="@/assets/images/svg/html-5.svg" alt="html">
        <img src="@/assets/images/svg/css-3.svg" alt="css">
        <img src="@/assets/images/svg/javascript.svg" alt="JS">
        <img src="@/assets/images/svg/nodejs.svg" alt="nodejs">
        <img src="@/assets/images/svg/vue.svg" alt="vuejs">
        <img src="@/assets/images/svg/mysql.svg" alt="mysql">
        <img src="@/assets/images/svg/git.svg" alt="git">
        <img src="@/assets/images/svg/linux-tux.svg" alt="linux">
        <img src="@/assets/images/svg/centos.svg" alt="centos">
        <img src="@/assets/images/svg/archlinux.svg" alt="Arch">
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.back-dark {
  background: #383634;
}
.skills-text {
  font-size: 2.4rem;
}
.skills-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: 50%;
  margin: 10px auto 0;
}
.skills-wrapper img {
  width: auto;
  height: 80px;
  margin: 16px;
}
@media (max-width: 768px) {
  .skills-wrapper {
    display: block;
  }
  .skills-wrapper img {
    width: 20%;
    height: auto;
    margin: auto;
  }
}
</style>
