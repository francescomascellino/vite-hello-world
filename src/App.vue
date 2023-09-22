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

<template>
	<!-- I COMPONENTI POSSO ESSERE AGGIUNTI AL TEMPLATE DI App.vue IN DUE MODI: -->
	<AppHero></AppHero>

	<AppTitle />

	<h2>{{ message }}</h2>
</template>