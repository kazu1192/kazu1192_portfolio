<template>
  <div class="flex-center">
    <div class="about">
      <h2 class="heading">ABOUT</h2>
      <div class="about-wrapper">
        <img src="@/assets/images/image01.jpg" alt="me">
        <div class="about-text-wrapper">
          <h2>{{ my_name }}</h2>
          <p>{{ about_msg }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      my_name: 'Kazuki Suzuki',
      about_msg: 'WEBエンジニア志望の26歳。大学でプログラミングを学び、SIer系企業の業務経験を2年経て、現在に至ります。好きな言語はRuby C# Javaです。趣味はパソコンいじり。好奇心旺盛で、興味を持ったことにずっと熱中する癖があります。WEB系の現場でずっと働きたいと考えております。'
    }
  }
}
</script>

<style scoped>
img {
  width: 30%;
  display: inline-block;
  margin: 0 15px;
}
p {
  line-height: 2.5;
}
.about {
  background-color: #EEE;
  color: #333;
  width: 50%;
}
.about-wrapper {
  margin: 30px;
}
.about-text-wrapper {
  display: inline-block;
  text-align: left;
  width: 60%;
  margin: 0 15px;
}
@media (max-width: 768px) {
  .about {
    width: 90%;
  }
  .about-text {
    line-height: 1.8;
  }
}
</style>
