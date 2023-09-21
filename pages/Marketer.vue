<template>
  <div class="marketer">
    <div class="common-white-box">
      <div class="common-white-box__inner">
        <div class="common-w-title">
          <div class="common-w-title__img-wrap">
            <img
              src="/images/this_is_me_2018-2022/neko_nomal.png"
              alt="普通の表情のねこ"
              oncontextmenu="return false;"
            />
          </div>
          <div class="common-w-title__text-wrap">
            <p>マーケターの姿</p>
          </div>
        </div>
        <div class="common-w-title__des">
          <p>webを中心に様々なマーケティングを経験してきました。</p>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2">
            <h2>総合広告のマーケティング</h2>
          </div>
          <div class="common-w-h2__des">
            <p>
              大学2年生の秋より、総合広告代理店ADKにインターン生としてジョイン。ブランディングやマーケティング思考を学び、コミュニケーション戦略立案やトレンド分析などを行ってきました。
            </p>
          </div>

          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>ブランディング</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/images/this_is_me_2018-2022/sogo_01.png"
                alt="白熱している議論の様子"
                oncontextmenu="return false;"
              />
            </div>
          </div>

          <div class="common-w-content__wrap width-max">
            <div class="common-w-h3">
              <h3>トレンド分析</h3>
            </div>
            <div class="common-w-content__flex">
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/sogo_02.png"
                  alt="トレンド分析の資料の1枚目"
                  oncontextmenu="return false;"
                />
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/sogo_03.png"
                  alt="トレンド分析の資料の2枚目"
                  oncontextmenu="return false;"
                />
              </div>
            </div>
          </div>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>WEBマーケティング</h2>
          </div>
          <div class="common-w-h2__des">
            <p>
              WEB広告運用やSEO対策、SNSマーケの戦略立案・運用などをしてきました。
            </p>
          </div>

          <div class="common-w-content__flex">
            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>WEB広告の運用</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/wm_01.png"
                  alt="運用報告資料"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>SEO対策</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/wm_02.png"
                  alt="アナリティクスの管理画面"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>インスタ運用戦略立案</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/wm_03.png"
                  alt="miroの画面"
                  oncontextmenu="return false;"
                />
              </div>
            </div>
          </div>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>事業立ち上げの際のマーケ</h2>
          </div>
          <div class="common-w-h2__des">
            <p>
              資料にあるSTP分析/ ペルソナ分析の他、 3C分析/ クロスSWOT分析/
              VRIO分析
              など、様々なフレームワークを用いて多角的に分析を行いました。
            </p>
          </div>

          <div class="common-w-content__wrap width-max">
            <div class="common-w-h3">
              <h3>資料一部抜粋</h3>
            </div>
            <div class="common-w-content__flex">
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/timimk_01.png"
                  alt="timiマーケ資料"
                  class="timi-shiryo-img"
                  oncontextmenu="return false;"
                />
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/timimk_02.png"
                  alt="timiマーケmiro"
                  class="timi-shiryo-img"
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
