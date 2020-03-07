<template>
  <nav id="navbar" class="navbar">
    <div class="container">
      <div class="navbar-brand">
        <a class="navbar-item is-paddingless" href="/">
          <img src="../assets/logoSygnet.svg" alt="logo image"/>
        </a>
        <div id="navbarBurger" class="navbar-burger burger">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navMenuIndex" class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item">
            <router-link to="/" class="has-text-dark">Home</router-link>
          </a>
          <a class="navbar-item">
            <router-link to="/" class="has-text-dark">About</router-link>
          </a>
          <a class="navbar-item">
            <router-link to="/" class="has-text-dark">Skills</router-link>
          </a>
          <a class="navbar-item">
            <router-link to="/" class="has-text-dark">Work</router-link>
          </a>
          <a class="navbar-item">
            <router-link to="/contact" class="has-text-dark">Contact</router-link>
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "MainNavigation"
};
</script>
