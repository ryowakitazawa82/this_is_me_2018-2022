<template>
  <div clas="first-movie">
    <div class="first-movie__main">
      <video
        src="video/thisisme.mp4"
        autoplay
        class="first-movie__main--video"
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
export default {};
</script>
