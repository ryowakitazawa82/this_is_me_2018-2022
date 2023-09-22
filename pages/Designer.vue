<template>
  <div class="marketer">
    <div class="common-white-box">
      <div class="common-white-box__inner">
        <div class="common-w-title">
          <div class="common-w-title__img-wrap">
            <img
              src="/this_is_me_2018-2022/images/neko_nomal.png"
              alt="普通の表情のねこ"
              oncontextmenu="return false;"
            />
          </div>
          <div class="common-w-title__text-wrap">
            <p>デザイナーの姿</p>
          </div>
        </div>
        <div class="common-w-title__des">
          <p>
            デザインは9割独学。初めはIllustratorがメインでしたが、最近はもっぱらXDを愛用。
          </p>
        </div>

        <div class="common-w-h2">
          <h2>WEBデザイン</h2>
        </div>
        <div class="common-w-h2__des">
          <p>
            個人で数件案件をこなした後に、ITベンチャーにデザイナーとしてジョインしました。
          </p>
        </div>

        <div class="common-w-content__flex">
          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>コーポレートサイト①</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/this_is_me_2018-2022/images/wd_01.png"
                alt="コーポレートサイト"
                class="large-img"
                oncontextmenu="return false;"
              />
            </div>
          </div>

          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>コーポレートサイト②</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/this_is_me_2018-2022/images/ohchp.png"
                alt="コーポレートサイト"
                class="large-img"
                oncontextmenu="return false;"
              />
            </div>
          </div>

          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>採用LP</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/this_is_me_2018-2022/images/wd_02.png"
                alt="採用LP"
                class="large-img"
                oncontextmenu="return false;"
              />
            </div>
          </div>

          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>広告LP</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/this_is_me_2018-2022/images/wd_03.png"
                alt="広告LP"
                class="large-img"
                oncontextmenu="return false;"
              />
            </div>
          </div>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>グラフィックデザイン</h2>
          </div>
          <div class="common-w-h2__des">
            <p>細かいパーツも基本的にAdobe Illustratorで自作していました。</p>
          </div>

          <div class="common-w-content__wrap width-max">
            <div class="common-w-h3">
              <h3>ポスティング広告</h3>
            </div>
            <div class="common-w-content__flex">
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/gd_01.png"
                  alt="ポスティング広告01"
                  class="posting-img"
                  oncontextmenu="return false;"
                />
              </div>
              <div class="common-w-h3__img plus-p-top">
                <img
                  src="/this_is_me_2018-2022/images/gd_01-2.png"
                  alt="ポスティング広告02"
                  class="posting-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>
          </div>

          <div class="common-w-content__flex">
            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>インスタ①</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/gd_02.png"
                  alt="インスタ"
                  class="grande-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

          <div class="common-w-content__flex">
            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>インスタ②</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/waka_insta.png"
                  alt="インスタ"
                  class="grande-img"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>広告バナー</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/this_is_me_2018-2022/images/gd_03.png"
                  alt="広告バナー"
                  class="grande-img"
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
