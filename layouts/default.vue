<template>
  <div>
    <Nuxt />
    <NavMenu></NavMenu>
  </div>
</template>

<script>
import NavMenu from "~/components/NavMenu.vue";
export default {
  components: {
    NavMenu,
  },
};
</script>
