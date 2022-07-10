<script setup>
	import { ref } from "vue";

	defineProps({
		msg: String,
	});

const count = ref(0);
</script>

<template>
	<div class="cell"></div>
</template>

<style scoped>
	a {
		color: #42b983;
	}

	.cell {
		height: 25px;
		width: 25px;
		border: 1px solid #001224;
		border-radius: 2px;
	}
</style>
