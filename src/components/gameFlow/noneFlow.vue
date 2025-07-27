<script setup lang="ts"></script>

<script setup lang="ts">
import lcuApi from "@/api/lcuApi";
</script>

<template>
	<div class="flex flex-col items-center">
		<div style="font-size: 100px">🍽️</div>
		<div style="font-size: 40px">等你开把游戏</div>
		<div class="mt-4">
			<button class="btn btn-primary" @click="lcuApi.playAgain">再来一局</button>
		</div>
	</div>
</template>

<style scoped></style>
