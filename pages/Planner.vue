<template>
  <div class="planner">
    <div class="common-white-box">
      <div class="common-white-box__inner">
        <div class="common-w-title">
          <div class="common-w-title__img-wrap">
            <img
              src="/this_is_me_2018-2022/images/neko_musu.png"
              alt="ムスッとしたねこ"
            />
          </div>
          <div class="common-w-title__text-wrap">
            <p>プランナーの姿</p>
          </div>
        </div>
        <div class="common-w-title__des">
          <p>
            挑戦と挫折を繰り返しながら、プランナーとして日々奮闘してきました。
          </p>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2">
            <h2>ビジネスコンテスト</h2>
          </div>
          <div class="common-w-h2__des">
            <p>
              大学在学中にビジネスコンテストに数度挑戦。大学3年秋に挑戦したビジコンでは、準決勝・決勝大会に進出しました。
            </p>
          </div>

          <div class="common-w-content__wrap width-max">
            <div class="common-w-h3">
              <h3>プレゼン動画</h3>
            </div>
            <div class="common-w-h3__video">
              <iframe
                src="https://www.youtube.com/embed/f7Yz55Faa-k"
                title="YouTube video player"
                frameborder="0"
                allowfullscreen
              ></iframe>
            </div>
            <div class="common-w-h3__sub-text">
              <p>※動画編集は他のチームメンバーが担当。</p>
            </div>
          </div>

          <div class="common-w-content__flex">
            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>チームロゴ</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/busicon_01.jpg"
                  alt="branch:チームロゴ"
                  oncontextmenu="return false;"
                />
              </div>
              <div class="common-w-h3__sub-text">
                <p>※美大生の方に制作していただきました。</p>
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>プランニング</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/busicon_02.jpg"
                  alt="branch:チームロゴ"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>事業企画資料</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/busicon_03.jpg"
                  alt="branch:チームロゴ"
                  oncontextmenu="return false;"
                />
              </div>
            </div>
          </div>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>新規事業企画</h2>
          </div>
          <div class="common-w-h2__des">
            <p>
              大学3年生の冬より、デートプランニングサービス『timidate（旧timitimi）』のローンチに向けて活動してきました。
            </p>
          </div>
          <div class="common-w-content__flex">
            <div class="common-w-content__wrap width-max">
              <div class="common-w-h3">
                <h3>サービス紹介動画</h3>
              </div>
              <div class="common-w-h3__video">
                <video
                  src="video/movietimi.mp4"
                  playsinline
                  controls="”true”"
                  oncontextmenu="return false;"
                ></video>
              </div>
              <div class="common-w-h3__sub-text">
                <p>※動画編集は他のチームメンバーが担当。</p>
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>投資家に向けた資料</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/timidate_02.png"
                  alt="branch:チームロゴ"
                  class="large-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>UI/UXの設計</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/timidate_03.png"
                  alt="branch:チームロゴ"
                  class="large-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>要件定義</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/timidate_04.png"
                  alt="branch:チームロゴ"
                  class="large-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>PLの作成</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/timidate_05.png"
                  alt="branch:チームロゴ"
                  class="large-img"
                  oncontextmenu="return false;"
                />
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
