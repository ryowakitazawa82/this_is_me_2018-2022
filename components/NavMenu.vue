<template>
  <div class="hamburger__btn" @click="toggleHamburger">
    <div class="hamburger__icon animate-hamburger">
      <span></span>
      <span></span>
    </div>
    <nav class="nav__wrap animate-hamburger">
      <ul class="nav__lists">
        <li class="nav__list">
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Planner">Planner</NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Marketer">Marketer</NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Designer">Designer</NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Developer">Developer</NuxtLink>
        </li>
        <li class="nav__list">
          <NuxtLink to="/Profile">Profile</NuxtLink>
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
