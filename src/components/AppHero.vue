<script>

export default
    {

        name: 'AppHero',

    }

</script>

<!-- QUESTO E' IL MARKUP CHE VERRA' IMPORTATO -->
<template>
    <div class="hero">
        <h1>Vue.js Hero component</h1>
    </div>
</template>

<!-- A SEGUIRE IL CSS DA APPLICARE AL MARKUP DI QUESTO COMPONENTE -->
<style>
.hero {
    padding: 1rem 0;
    height: 125px;
    color: darkred;
    background-image: url(..//assets/vue.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    display: flex;
    align-items: center;
    flex-direction: column;
}
</style>

