<script setup>
	import { ref } from "vue"
	import GridCell from "./gridCell.vue"

	defineProps({
		amount: Number,
});

const count = ref(0);
</script>

<template>
	<div class="grid-container">
		<template v-for="index in 300" :key="index">
			<GridCell/>
		</template>
	</div>
</template>

<style scoped>
	.grid-container {
		display: grid;
		grid-template-columns: repeat(30, 25px);
		gap: 5px;
		justify-content: center;
	}
</style>
