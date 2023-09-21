<template>
  <div class="dev">
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
            <p>ディベロッパーの姿</p>
          </div>
        </div>
        <div class="common-w-title__des dev-title__des">
          <p>日々勉強中。。。</p>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2">
            <h2>スキルセット</h2>
          </div>
          <div class="common-w-content__wrap dev-content__wrap dev-width-max">
            <div class="common-w-h3__img">
              <img
                src="/images/this_is_me_2018-2022/skillset_dev.png"
                alt="スキルセット"
                oncontextmenu="return false;"
              />
            </div>
          </div>
        </div>

        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>WEBサイト制作</h2>
          </div>
          <div class="common-w-h2__des">
            <p>HTML/SCSS/JavaScript</p>
          </div>

          <div class="common-w-content__wrap width-max">
            <div class="common-w-h3">
              <h3>LP/コーポレートサイト</h3>
            </div>
            <ul class="dev-site__contents">
              <li class="dev-site__content">
                <a href="http://eishin-develop.sakura.ne.jp/kyoei-denki/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_w_01.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
              <li class="dev-site__content">
                <a href="https://reactwall.co.jp/recruit-lp/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_site_02.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
              <li class="dev-site__content">
                <a href="https://www.iskc.co.jp/jinzai/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_site_03.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
              <li class="dev-site__content">
                <a href="https://kawasakidaishi-midori-ph.com/recruit/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_site_04.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
              <li class="dev-site__content">
                <a href="https://ufc-llc.jp//recruit.php/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_site_05.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
              <li class="dev-site__content">
                <a href="https://www.firstcontact.co.jp/recruit/">
                  <div class="common-w-h3__img">
                    <img
                      src="/images/this_is_me_2018-2022/dev_site_06.png"
                      alt="web制作"
                      oncontextmenu="return false;"
                    /></div
                ></a>
              </li>
            </ul>
          </div>
        </div>
        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>webアプリ開発</h2>
          </div>
          <div class="common-w-h2__des">
            <p>React/Vue/Nuxt</p>
          </div>

          <div class="common-w-content__flex">
            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>Trello(Vue)</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/dev_a_01.png"
                  alt="webアプリ開発"
                  oncontextmenu="return false;"
                />
              </div>
            </div>

            <div class="common-w-content__wrap">
              <div class="common-w-h3">
                <h3>Trello(React)</h3>
              </div>
              <div class="common-w-h3__img">
                <img
                  src="/images/this_is_me_2018-2022/dev_a_02.png"
                  alt="webアプリ開発"
                  oncontextmenu="return false;"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="fadein" v-scroll="handleScroll">
          <div class="common-w-h2 plus-p-top">
            <h2>ゲーム開発</h2>
          </div>
          <div class="common-w-h2__des">
            <p>Unity/C#</p>
          </div>

          <div class="common-w-content__wrap">
            <div class="common-w-h3">
              <h3>ブロック崩しゲーム</h3>
            </div>
            <div class="common-w-h3__img">
              <img
                src="/images/this_is_me_2018-2022/dev_g_01.png"
                alt="timiマーケ資料"
                oncontextmenu="return false;"
              />
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
