<template>
  <div class="home-animation__wrap" id="home-animation-mask">
    <div class="home-animation">
      <span>THIS IS ME IN 2018~2022</span>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    this.Animate();
  },
  methods: {
    Animate() {
      const homeAnimationMask = document.getElementById("home-animation-mask");
      setTimeout(() => {
        homeAnimationMask.classList.add("hidden");
      }, 2600);
    },
  },
};
</script>
