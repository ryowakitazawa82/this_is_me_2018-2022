<template>
  <div clas="first-movie">
    <div class="first-movie__mask" id="movie-mask">
      <div class="first-movie__mask--inner">
        <p class="first-movie__mask--txt">
          ※音声が出ますので、<br class="sp-only" />音量にご注意ください。
        </p>
        <div class="first-movie__mask--btn" @click="isOk">OK!</div>
      </div>
    </div>
    <div class="first-movie__main">
      <video
        src="video/thisIsMeUni.mp4"
        playsinline
        muted
        class="first-movie__main--video"
        id="video"
        oncontextmenu="return false;"
      ></video>
    </div>

    <div class="first-movie__next-button">
      <NuxtLink to="/">
        <p class="first-movie__next-button--txt">SKIP</p>
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const video = document.getElementById("video");
    video.addEventListener("ended", function () {
      window.location.href = "/";
    });
  },
  methods: {
    isOk() {
      const movieMask = document.getElementById("movie-mask");
      movieMask.classList.add("ready-ok");
      video.muted = false;
      video.play();
    },
  },
  layout: "normal",
};
</script>
