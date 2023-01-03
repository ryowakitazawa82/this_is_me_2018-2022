<template>
  <div>
    <Nuxt />
    <div class="hamburger__btn" @click="toggleHamburger">
      <div class="hamburger__icon animate-hamburger">
        <span></span>
        <span></span>
      </div>
      <nav class="nav__wrap animate-hamburger"></nav>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    toggleHamburger() {
      const hamburgerAnimationElem =
        document.querySelectorAll(".animate-hamburger");
      hamburgerAnimationElem.forEach((i) => i.classList.toggle("is-active"));
    },
  },
};
</script>
