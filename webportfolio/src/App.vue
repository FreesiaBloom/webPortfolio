<template>
  <main class="section">
    <MainNavigation />
    <router-view />
  </main>
</template>

<script>
import MainNavigation from "@/components/MainNavigation.vue";

export default {
  name: "Home",
  components: {
    MainNavigation
  }
};
</script>

<style lang="scss">
@import "./assets/styles/main.scss";
</style>
