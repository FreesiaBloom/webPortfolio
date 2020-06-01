<template>
  <header class="section">
    <nav
      class="navbar is-transparent"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item" href="/">
            <img
              src="../assets/images/logoSygnet.svg"
              alt="Agata Jasinska | Front-end Developerand UI designer"
              height="48"
            />
          </a>
          <a
            class="navbar-burger"
            role="button"
            aria-label="menu"
            aria-expanded="false"
            data-target="#navMenu"
          >
            <span aria-hidden="true"></span><span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>
        <div class="navbar-menu" id="navMenu">
          <div class="navbar-start"></div>
          <div class="navbar-end">
            <div class="navbar-item">
              <a
              class="button is-primary is-outlined is-rounded"
                href="/contact">
                <router-link to="/contact" class="has-text-dark">Contact</router-link>
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <!-- <nav id="navbar" class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item is-paddingless" href="/">
            <img src="../assets/images/logoSygnet.svg" alt="logo image" />
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
              <router-link to="/" class="has-text-dark">About</router-link>
            </a>
            <a class="navbar-item">
              
            </a>
          </div>
        </div>
      </div>
    </nav> -->
  </header>
</template>

<script>
export default {
  name: "MainNavigation"
};
</script>
