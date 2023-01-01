<template>
  <div clas="first-movie">
    <div class="first-movie__mask">
    </div>
    <div class="first-movie__main">
      <video
        src="video/thisisme.mp4"
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
    // const video = document.getElementById("video");
    // video.addEventListener("canplay", () => {
    //   video.classList.add("loaded");
    // });

    const button = document.getElementById("button");
    button.addEventListener("click", function () {
      video.muted = false;
      video.play();
    });
  },
};
</script>
