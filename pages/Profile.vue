<template>
  <div class="profile">
    <div class="common-white-box">
      <div class="common-white-box__inner">
        <div class="profile">
          <div class="my-name profile__my-name">
            <div class="my-name__img">
              <img
                src="/images/this_is_me_2018-2022/kity_icon.png"
                oncontextmenu="return false;"
              />
            </div>
            <div class="my-name__text">
              <h3>Kitazawa Ryowa</h3>
              <h2>北沢 亮和</h2>
            </div>
          </div>
        </div>

        <div class="profile__top_img sp-only fadein" v-scroll="handleScroll">
          <img
            src="/images/this_is_me_2018-2022/pro_01.jpg"
            alt="北沢亮和"
            oncontextmenu="return false;"
          />
        </div>

        <div class="profile__inner fadein" v-scroll="handleScroll">
          <div class="common-w-content__flex">
            <div class="profile__top_img pc-only">
              <img
                src="/images/this_is_me_2018-2022/pro_01.jpg"
                alt="北沢亮和"
                oncontextmenu="return false;"
              />
            </div>
            <div class="profile-content__wrap">
              <div class="profile__title">
                <div class="profile-title__img-wrap">
                  <img
                    src="/images/this_is_me_2018-2022/neko_nomal.png"
                    alt="普通の表情のねこ"
                    oncontextmenu="return false;"
                  />
                </div>
                <div class="profile-title__text-wrap">
                  <p>基本の情報</p>
                </div>
              </div>
              <div class="profile__main-text">
                <p class="en">Name</p>
                <p class="jp">北沢 亮和 (キタザワ リョウワ）</p>
              </div>
              <div class="profile__main-text">
                <p class="en">University</p>
                <p class="jp">法政大学 経済学部 経済学科</p>
              </div>
              <div class="profile__main-text">
                <p class="en">From</p>
                <p class="jp">神奈川県 厚木市</p>
              </div>
              <div class="profile__main-text">
                <p class="en">Birth Day</p>
                <p class="jp">1999年8月2日（平成11年）</p>
              </div>
            </div>

            <div class="profile-content__wrap">
              <div class="profile__title">
                <div class="profile-title__img-wrap">
                  <img
                    src="/images/this_is_me_2018-2022/neko_aa.png"
                    alt="ああって感じのねこ"
                    oncontextmenu="return false;"
                  />
                </div>
                <div class="profile-title__text-wrap">
                  <p>真面目な情報</p>
                </div>
              </div>
              <div class="profile__main-text">
                <p class="en">Vision</p>
                <p class="jp">クリエイトで人を笑顔に</p>
              </div>
              <div class="profile__main-text">
                <p class="en">Position</p>
                <p class="jp">
                  事業プランナー<br />
                  総合/WEB マーケター<br />
                  グラフィック/WEB デザイナー<br />
                  フロントエンド/ゲームエンジニア
                </p>
              </div>
              <div class="profile__main-text">
                <p class="en">Skill</p>
                <p class="jp">
                  <img
                    src="/images/this_is_me_2018-2022/skillset.png"
                    oncontextmenu="return false;"
                  />
                </p>
              </div>
              <div class="profile__main-text">
                <p class="en">Qualification</p>
                <p class="jp">
                  マーケティング・ビジネス実務検定B級<br />
                  TOEIC 790<br />
                  日商簿記検定3級<br />
                  普通自動車免許<br />
                  全国珠算検定1級
                </p>
              </div>
            </div>

            <div class="profile-content__wrap">
              <div class="profile__title">
                <div class="profile-title__img-wrap">
                  <img
                    src="/images/this_is_me_2018-2022/neko_naki.png"
                    alt="泣き顔のねこ"
                    oncontextmenu="return false;"
                  />
                </div>
                <div class="profile-title__text-wrap">
                  <p>その他の情報</p>
                </div>
              </div>
              <div class="profile__main-text">
                <p class="en">Achievement</p>
                <p class="jp">
                  <span>エンカレッジ主催ビジネスコンテスト</span><br />
                  ビジネス甲子園2020 準決勝・決勝進出
                </p>
                <p class="jp plus-p-top">
                  <span>株式会社GameWith Internship</span><br />
                  『GAME CHANGER』準優勝
                </p>
                <p class="jp plus-p-top">
                  <span>株式会社ADKホールディングス Internship</span><br />
                  『ADK Breakthrough Camp』優秀賞
                </p>
                <p class="jp plus-p-top">
                  <span>法政大学自主マスコミ講座 </span><br />
                  『CM企画制作コンペ』最優秀賞
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    handleScroll: function (evt, el) {
      if (window.scrollY > 50) {
        el.setAttribute(
          "style",
          "opacity: 1; transform: translate3d(0, -10px, 0)"
        );
      }
      return window.scrollY > 100;
    },
  },
};
</script>

<style></style>
