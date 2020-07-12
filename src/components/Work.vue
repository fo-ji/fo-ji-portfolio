<template>
  <Work>
    <div class="work">
      <div class="container__title">
        <div class="container__title--text">Work</div>
      </div>
      <div class="container__work">
        <div class="container__work--left">
          <div class="app">
            <div class="app__title"><span>個人制作</span></div>
            <div class="app__content">
              <div class="image__content">
                <a href="https://home-select-shop.herokuapp.com/"  target="_blank">
                  <img src="https://i.gyazo.com/c3ea284a22ff825c072c4817afbd90f8.png" class="site-image" alt="キャプチャー画像">
                </a>
              </div>
              <div class="text__content">
                <div class="text__content--name lead">HomeSelectShop</div>
                <div class="text__content--skill">
                  <div class="content__label">使用技術：</div>
                  <div class="content__skill">
                    <em>haml & scss</em> / <em>Ruby</em> / <em>Rails</em> / <em>jQuery</em> / <em>Docker</em> / <em>MySQL</em> (development) / <em>PostgreSQL</em> (production) / <em>Heroku</em> / <em>CircleCI</em>
                  </div>
                </div>
                <div class="text__content--intro">詳細は<a href="https://github.com/fo-ji/home_select_shop" target="_blank">README</a>よりご確認ください。</div>
              </div>
            </div>
          </div>
        </div>
        <div class="container__work--center">
          <div class="app">
            <div class="app__title"><span>チーム制作</span></div>
            <div class="app__content">
              <div class="image__content">
                <a href="http://18.176.134.115/" target="_blank">
                  <img src="https://camo.githubusercontent.com/8bb2c3102b5c64ede39be08b0219a036bdb4737d/68747470733a2f2f6779617a6f2e636f6d2f36613865613931393836343232656534393464326230313533373439633331352e6a7067" class="site-image" alt="キャプチャー画像">
                </a>
              </div>
              <div class="text__content">
                <div class="text__content--name lead">フリマサイト(クローン制作)</div>
                <div class="text__content--skill">
                  <div class="content__label">使用技術：</div>
                  <div class="content__skill">
                    <em>haml & scss</em> / <em>Ruby</em> / <em>Rails</em> / <em>jQuery</em> / <em>MySQL</em> / <em>AWS</em>
                  </div>
                </div>
                <div class="text__content--intro">詳細は<a href="https://github.com/fo-ji/freemarket_sample_60c" target="_blank">README</a>よりご確認ください。</div>
              </div>
            </div>
          </div>
        </div>
        <div class="container__work--right">
          <div class="app">
            <div class="app__title"><span>ポートフォリオサイト</span></div>
            <div class="app__content">
              <div class="image__content">
                <a href="https://fo-ji-portfolio.web.app/" target="_blank">
                  <img src="https://i.gyazo.com/3d90a4156da3974bf20abda7debca053.png" class="site-image" alt="キャプチャー画像">
                </a>
              </div>
              <div class="text__content">
                <div class="text__content--name lead">fo-ji's Portfolio</div>
                <div class="text__content--skill">
                  <div class="content__label">使用技術：</div>
                  <div class="content__skill">
                    <em>HTML & scss</em> / <em>Vue.js</em> / <em>firebase</em>
                  </div>
                </div>
                <div class="text__content--intro">詳細は<a href="https://github.com/fo-ji/fo-ji-portfolio" target="_blank">README</a>よりご確認ください。</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Work>
</template>

<script>
// @ is an alias to /src
import Work from '@/components/Work.vue'

export default {
  name: 'work',
  components: {
    Work
  }
}
</script>
