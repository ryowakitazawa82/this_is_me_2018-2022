<template>
  <div class="index">
    <NuxtLink to="/Profile">
      <div class="my-name">
        <div class="my-name__img">
          <img
            src="/this_is_me_2018-2022/images/kity_icon.png"
            oncontextmenu="return false;"
          />
        </div>
        <div class="my-name__text">
          <h3>Kitazawa Ryowa</h3>
          <h2>北沢 亮和</h2>
        </div>
      </div>
    </NuxtLink>
    <div class="content-wrap">
      <div class="business-side">
        <div class="index-title">
          <h2>ビジネスサイド</h2>
        </div>
        <NuxtLink to="/Planner">
          <div class="index__planner-link large-box">
            <div class="large-box__img-wrap">
              <img
                src="/this_is_me_2018-2022/images/neko_musu.png"
                alt="ムスッとしたねこ"
                oncontextmenu="return false;"
              />
            </div>
            <div class="large-box__text-wrap">
              <p>プランナーの姿</p>
            </div>
          </div>
        </NuxtLink>
        <NuxtLink to="/Marketer">
          <div class="index__planner-link large-box">
            <div class="large-box__img-wrap">
              <img
                src="/this_is_me_2018-2022/images/neko_nomal.png"
                alt="普通の表情のねこ"
                oncontextmenu="return false;"
              />
            </div>
            <div class="large-box__text-wrap">
              <p>マーケターの姿</p>
            </div>
          </div>
        </NuxtLink>
      </div>
      <div class="creator-side">
        <div class="index-title">
          <h2>クリエイターサイド</h2>
        </div>
        <NuxtLink to="/Designer">
          <div class="index__planner-link large-box">
            <div class="large-box__img-wrap">
              <img
                src="/this_is_me_2018-2022/images/neko_aa.png"
                alt="ああって感じのねこ"
                oncontextmenu="return false;"
              />
            </div>
            <div class="large-box__text-wrap">
              <p>デザイナーの姿</p>
            </div>
          </div>
        </NuxtLink>
        <NuxtLink to="/Developer">
          <div class="index__planner-link large-box">
            <div class="large-box__img-wrap">
              <img
                src="/this_is_me_2018-2022/images/neko_naki.png"
                alt="泣き顔のねこ"
                oncontextmenu="return false;"
              />
            </div>
            <div class="large-box__text-wrap">
              <p>ディベロッパーの姿</p>
            </div>
          </div>
        </NuxtLink>
      </div>
    </div>
    <div class="index-title bonus-title pc-only">
      <h2>おまけ</h2>
    </div>
    <div class="sub-corner">
      <div class="sub-corner__other medium-box">
        <NuxtLink to="/Other">
          <p>その他</p>
        </NuxtLink>
      </div>
      <div class="sub-corner__column medium-box">
        <NuxtLink to="/Column">
          <p>コラム</p>
        </NuxtLink>
      </div>
    </div>
    <HomeAnimation></HomeAnimation>
  </div>
</template>

<script>
import HomeAnimation from "~/components/HomeAnimation.vue";
export default {
  components: {
    HomeAnimation,
  },
};
</script>
