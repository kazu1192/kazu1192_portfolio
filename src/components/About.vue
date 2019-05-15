<template>
  <section class="about" id="about">
    <h2 class="heading">ABOUT ME</h2>
    <p class="about-text">
    大学でプログラミングを学び、SIer系企業の業務経験を2年経て、現在に至ります。<br>
    好きな言語はRuby C# Javaです。趣味はパソコンいじり。<br>
    好奇心旺盛で、興味を持ったことにずっと熱中する癖があります。<br>
    WEB系の現場でずっと働きたいなあと思っております。
    </p>
  </section>
</template>

<script>
</script>

<style>
.about {
  padding: 80px 30px;
  background-color: #fff;
  color: #333;
}
.heading {
  display: inline-block;
  position: relative;
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
.about-text {
  margin: 30px 0;
  line-height: 2.5;
}
</style>
