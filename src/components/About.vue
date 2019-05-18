<template>
  <div class="flex-center">
    <div class="about">
      <h2 class="heading">ABOUT</h2>
      <div class="about-wrapper">
        <img src="../assets/images/image01.jpg" alt="kazuki">
        <div class="about-text-wrapper">
          <h2>Kazuki Suzuki</h2>
          <p>
          WEBエンジニア志望の26歳。<br>
          大学でプログラミングを学び、SIer系企業の業務経験を2年経て、現在に至ります。<br>
          好きな言語はRuby C# Javaです。趣味はパソコンいじり。<br>
          好奇心旺盛で、興味を持ったことにずっと熱中する癖があります。<br>
          WEB系の現場でずっと働きたいと考えております。
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.about {
  background-color: #EEE;
  color: #333;
  width: 60%;
}
.about-wrapper {
  margin: 30px;
}
.about-wrapper img {
  width: 250px;
  display: inline-block;
  margin-right: 30px;
}
.about-text-wrapper {
  display: inline-block;
  text-align: left;
}
.about-text-wrapper p {
  line-height: 2.5;
}
@media (max-width: 768px) {
  .about-text {
    line-height: 1.8;
  }
}
</style>
