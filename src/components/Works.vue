<template>
<div class="flex-center">
  <div class="works">
    <h2 class="heading">WORKS</h2>
    <div class="works-wrapper">
      <div class="work-box">
        <figure>
          <img src="@/assets/images/work01.jpg"/>
          <figcaption>
            <h3>CaveView</h3>
            <p>
              動画配信サイトのCavetubeをAndroidで見られるようにしました。<br>
              起動と同時に配信一覧を取得、タップすると再生画面に遷移します。<br>
              制作環境:Java AndroidStudio
            </p>
          </figcaption>
        </figure>
      </div>
      <div class="work-box">
        <figure>
          <img src="@/assets/images/work02.jpg"/>
          <figcaption>
            <h3>DiscordBot</h3>
            <p>
              Discordで利用可能なBotを作成しました。<br>
              コマンドや会話に反応して動作します。<br>
              制作環境: Ruby Vim
            </p>
          </figcaption>
        </figure>
      </div>
      <div class="work-box">
        <figure>
          <img src="@/assets/images/work03.png"/>
          <figcaption>
            <h3>Kazuki's Portfolio</h3>
            <p>
              本サイトです。<br>
              リンクスクロールは vue-smoothscroll を使用しました。<br>
              また、制作にあたってdocker,docker-composeにて環境構築しました。<br>
              制作環境: Vue.js HTML5 CSS3 Vim docker docker-compose
            </p>
          </figcaption>
        </figure>
      </div>
    </div>
  </div>
</div>
</template>

<style scoped>
img {
  width: 100%;
  height: 100%;
}
figure {
  position: relative;
  overflow: hidden;
}
figcaption {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 2;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,.6);
  -webkit-transition: .3s;
  transition: .3s;
  opacity: 0;
}
figcaption p {
  margin: 10px;
}
figure:hover figcaption {
  opacity: 1;
}
.works {
  width: 70%;
  padding: 80px 0;
}
.works-wrapper {
  margin: 10px auto 0;
}
.work-box {
  max-width: 300px;
  display: inline-block;
}
@media (max-width: 768px) {
  figure {
    width: 100%;
    height: 100%;
    margin: 0;
  }
  .works {
    width: 90%;
  }
}
</style>
