<template>
	<div id="pokedex">
		<Pokedex />
	</div>
</template>

<script>
	import Pokedex from './components/Pokedex.vue';

	export default {
		name: 'App',
		components: {
			Pokedex,
		},
	};
</script>

<style lang="scss" scoped>
#pokedex {
  display: flex;
	flex-direction: column;
	min-height: 100vh;
	max-width: 1000px;
	margin: 0 auto;
	padding: 24px;
}
</style>
