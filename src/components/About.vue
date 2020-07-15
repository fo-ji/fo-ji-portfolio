<template>
  <About>
    <div class="about">
      <div class="container__about">
        <div class="container__about--left">
          <img src="@/assets/img/profile-photo.png" class="profile__img" alt="プロフィール写真" width="400" height="400"/>
        </div>
        <div class="container__about--right">
          <div class="title">About</div>
          <div class="text__area">
            <p>東京在中で健食・医薬品メーカーで勤務中の王子史也です。<br><br>2019年10月より独学、スクールでの学習を通じて日々、制作に励んでいます。<br>エンジニアとして、サービスを通じて「人を充実させる手伝いをしたい」ことを目標に転職活動中です。<br><br>言語としてRubyを主に使用しています。将来的には大規模な開発にも携わりたいと考え、Javaも学習中です。</p>
          </div>
        </div>
      </div>
    </div>
  </About>
</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'

export default {
  name: 'about',
  components: {
    About
  }
}
</script>
