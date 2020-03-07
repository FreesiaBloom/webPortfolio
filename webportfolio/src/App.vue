<template>
  <section class="section" id="app">
    <nav class="navbar" id="nav">
      <div class="nav-item">
        <router-link to="/">Home</router-link> |
      </div>
      <div class="nav-tem">
        <router-link to="/contact">Contact</router-link>
      </div>
    </nav>
    <router-view />
  </section>
</template>

<style lang="scss">
@import "~bulma/css/bulma.css";
@import "./assets/main.scss";
</style>
