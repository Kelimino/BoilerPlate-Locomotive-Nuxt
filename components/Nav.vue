<template>
  <div>
    <div class="nav" :style="navStyle">
      <nuxt-link to="/">Accueil</nuxt-link>
      <nuxt-link to="projets">Projets</nuxt-link>
      <nuxt-link to="approche">Approche</nuxt-link>
      <nuxt-link to="apropos">À propos</nuxt-link>
    </div>
  </div>
</template>

<script>
import { store } from "~/store/store.js"

export default {
  computed: {
    navStyle() {
      console.debug("STORE ISNAMVAL", store.isNavSmall)
      return {
        padding: store.isNavSmall ? "4px 0" : "10px 0"
      }
    }
  }
};
</script>

<style scoped>
.nav {
  position: fixed;
  top: 0;
  left: 0;
  background: #2e495e;
  padding: 20px 0;
  width: 100%;
  z-index: 999;
}

.nav a {
  color: #fff;
}
</style>
