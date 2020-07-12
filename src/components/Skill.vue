<template>
  <Skill>
    <div class="skill">
      <div class="container__title">
        <div class="container__title--text">Skill</div>
      </div>
      <div class="container__skill">
        <div class="container__skill--left">
          <div class="front">
            <div class="front__title"><span>フロントエンド</span></div>
            <div class="front__content">
              <ul class="front__content--list">
                <li class="list__skill">
                  <div class="list__skill--name">HTML & CSS</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star5.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      主に<em>haml</em>, <em>scss</em>を用いて実装します。<br>クローンサイトを一通り制作できるレベルです。<br>本ポートフォリオサイトはレスポンシブ対応しています。
                    </div>
                  </div>
                </li>
                <li class="list__skill">
                  <div class="list__skill--name">Javascript</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star3.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      主に<em>jQuery</em>を用いて実装しています。<br>インクリメンタルサーチ、画像アップロード時のプレビュー表示、タブスイッチなど実装できます。<br>本ポートフォリオでは<em>Vue.js</em>使用しましたが、まだまだ勉強中です。
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="container__skill--center">
          <div class="back">
            <div class="back__title"><span>バックエンド</span></div>
            <div class="back__content">
              <ul class="back__content--list">
                <li class="list__skill">
                  <div class="list__skill--name">Ruby & Ruby on Rails</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star5.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      一般的なECサイトで使用される機能（ユーザー管理、商品出品、カート機能）やチャットやいいね、お気に入り機能など実装できます。
                    </div>
                  </div>
                </li>
                <li class="list__skill">
                  <div class="list__skill--name">SQL</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star4.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      主に<em>MySQL</em>を使用します。<br>本番環境のみ<em>Postgresql</em>を使用した経験があります。
                    </div>
                  </div>
                </li>
                <li class="list__skill">
                  <div class="list__skill--name">Java</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star1.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      実績はありませんが、まずは体系的に学習する為、Java Broze取得に向け日々学習しています。
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="container__skill--right">
          <div class="tool">
            <div class="tool__title"><span>ツール・その他</span></div>
            <div class="tool__content">
              <ul class="tool__content--list">
                <li class="list__skill">
                  <div class="list__skill--name">Github</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star4.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      スクールで<em>Github</em>を用いたチーム開発の経験があります。
                    </div>
                  </div>
                </li>
                <li class="list__skill">
                  <div class="list__skill--name">AWS</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star3.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      <em>EC2</em>, <em>S3</em>を用いた開発経験があります。<br>
                    </div>
                  </div>
                </li>
                <li class="list__skill">
                  <div class="list__skill--name">Docker</div>
                  <div class="list__skill--evaluate">
                    <div class="label">経験：</div>
                    <img src="@/assets/img/star2.png" class="star" alt="スキルの評価"/>
                  </div>
                  <div class="list__skill--intro">
                    <div class="label">実績：</div>
                    <div class="introduction">
                      個人制作物の「HomeSelctShop」で使用しています。<br>CircleCIと連携させ、Rspecのテストをデプロイ時に自動化しています。
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Skill>
</template>

<script>
// @ is an alias to /src
import Skill from '@/components/Skill.vue'

export default {
  name: 'skill',
  components: {
    Skill
  }
}
</script>
