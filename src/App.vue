<template>
	<div id="app">
		<CommonDashboard/>
	</div>
</template>

<script>
import CommonDashboard from './components/dashboard/CommonDashboard.vue';

export default {
	name: 'App',
	components: {
		CommonDashboard,
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	color: #2c3e50;
}
</style>
