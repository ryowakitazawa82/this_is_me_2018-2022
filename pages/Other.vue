<template>
  <div class="other">
    <div class="common-white-box">
      <div class="common-white-box__inner">
        <div class="common-w-title">
          <div class="common-w-title__text-wrap">
            <p>その他</p>
          </div>
        </div>
        <div class="common-w-title__des other-title__des">
          <p>その他やってきた活動ここに載せます！</p>
        </div>

        <div class="common-w-h2">
          <h2>WEBデザイナーの育成</h2>
        </div>
        <div class="common-w-h2__des">
          <p>
            『デザイナーとしての技術スタックを継承したい』『学習することの良さを布教したい』といった想いから、デザインを勉強したい人の学習支援を開始。（2021年11月25日現在は5名を支援）
          </p>
        </div>

        <div class="common-w-content__wrap">
          <div class="common-w-h3">
            <h3>メインビジュアル</h3>
          </div>
          <div class="common-w-h3__img">
            <img
              src="/this_is_me_2018-2022/images/other_01.jpg"
              alt="webデザイナー育成講座"
            />
          </div>
        </div>

        <div class="common-w-h2 plus-p-top">
          <h2>インターンの採用人事</h2>
        </div>
        <div class="common-w-h2__des">
          <p>
            準備期間がほとんどなく始まったインターンの新期生採用。採用広報から採用人事体制の構築まで急ピッチで進め、無事完遂することができました。
          </p>
        </div>

        <div class="common-w-content__wrap">
          <div class="common-w-h3">
            <h3>仮置きだよ</h3>
          </div>
          <div class="common-w-h3__img">
            <img src="/this_is_me_2018-2022/images/sogo_01.png" alt="仮置き" />
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
