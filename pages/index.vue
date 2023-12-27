<template>
	<div class="lg:grid lg:grid-cols-12 lg:gap-10">
		<Sidebar class="hidden lg:col-span-2 lg:block" />

		<main class="container lg:col-span-10">
			<Header />
			<StatusCard />
		</main>
	</div>
</template>

<script setup>
import Header from '../components/Header.vue'
</script>
