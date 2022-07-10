<script setup>
	import gridContainer from "./components/gridContainer.vue";
</script>

<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<h1>Vue Pathfinder</h1>
	<h4>calculates the shortest path between two points using different algorithms</h4>
	<gridContainer amount="900" />
</template>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
