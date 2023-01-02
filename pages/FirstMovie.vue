<template>
  <div clas="first-movie">
    <div class="first-movie__mask" id="movie-mask">
      <div class="first-movie__mask--inner">
        <p class="first-movie__mask--txt">
          ※音声が出ますので、音量にご注意ください。
        </p>
        <div class="first-movie__mask--btn" id="ready-ok-button">OK!</div>
      </div>
    </div>
    <div class="first-movie__main">
      <video
        src="video/thisIsMeUni.mp4"
        playsinline
        muted
        class="first-movie__main--video"
        id="video"
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
    const movieMask = document.getElementById("movie-mask");
    const readyOkButton = document.getElementById("ready-ok-button");
    readyOkButton.addEventListener("click", function () {
      movieMask.classList.add("ready-ok");
      video.muted = false;
      video.play();
    });
    video.addEventListener("ended", function () {
      window.location.href = "/";
    });
  },
  layout: 'normal',
};
</script>
