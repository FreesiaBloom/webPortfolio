<template>
  <section class="section welcome-view">
    <div class="container">
      <div class="block titles">
        <h1 class="title center">
          Hello, I'm Agata
        </h1>
        <p class="subtitle center">
          Frontend developer and UI designer based in Szczecin, Poland.
        </p>
      </div>
      <div class="block center image-block">
        <img
          class="image-welcome-view"
          src="../assets/images/400x400.jpg"
          alt=""
        />
      </div>
      <div class="block center">
        <button class="button ">
          Get to know me 
          <font-awesome-icon class="margin-icon" icon="chevron-right" />
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "WelcomeView"
};
</script>
