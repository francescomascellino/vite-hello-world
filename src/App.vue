<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default
  {
    data() {
      return {
        message: "Hello Vite"
      }
    },

    components: {
      AppTitle,
      AppHero
    }
  }

</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

<template>
  <AppHero></AppHero>

  <AppTitle />

  <h2>{{ message }}</h2>
</template>