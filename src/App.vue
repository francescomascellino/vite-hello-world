<script>

// OGNI COMPONENTE VIENE IMPORTATO E ASSEGNATO A UN IDENTIFICATIVO
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default
  {
    data() {
      return {
        message: "Hello Vite"
      }
    },

    // DOPO DEVONO ESSERE DICHIARATI NEL COMPONENT OBJECT
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
  <!-- I COMPONENTI POSSO ESSERE AGGIUNTI AL TEMPLATE DI App.vue IN DUE MODI: -->
  <AppHero></AppHero>

  <AppTitle />

  <h2>{{ message }}</h2>
</template>