<template>
  <div class="hamburger__btn" @click="toggleHamburger">
    <div class="hamburger__icon animate-hamburger">
      <span></span>
      <span></span>
    </div>
    <nav class="nav__wrap animate-hamburger">
      <ul class="nav__lists">
        <li class="nav__list">
          <NuxtLink to="/"><p class="nav__list--txt">Home</p></NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Planner"
            ><p class="nav__list--txt">Planner</p></NuxtLink
          >
        </li>
        <li class="nav__list">
          <NuxtLink to="/Marketer"
            ><p class="nav__list--txt">Marketer</p></NuxtLink
          >
        </li>
        <li class="nav__list">
          <NuxtLink to="/Designer"
            ><p class="nav__list--txt">Designer</p></NuxtLink
          >
        </li>
        <li class="nav__list">
          <NuxtLink to="/Developer"
            ><p class="nav__list--txt">Developer</p></NuxtLink
          >
        </li>
        <li class="nav__list">
          <NuxtLink to="/Profile"
            ><p class="nav__list--txt">Profile</p></NuxtLink
          >
        </li>
      </ul>
    </nav>
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
