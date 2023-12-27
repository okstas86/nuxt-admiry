<template>
	<section class="grid gap-3 my-3 md:grid-cols-4">
		<div
			class="flex items-center justify-end h-[100px] rounded-lg border bg-card"
		>
			<div class="border rounded-full p-4">
				<Icon
					name="heroicons:shopping-cart"
					class="w-7 h-7 text-muted-foreground"
				/>
			</div>
			<div class="flex flex-col items-center mx-7">
				<p class="text-xl font-extrabold">15852</p>
				<p class="text-sm font-madium">Total Sales</p>
			</div>
		</div>
		<div class="flex items-center justify-end rounded-lg border bg-card">
			<div class="border rounded-full p-4">
				<Icon name="bi:currency-dollar" class="w-7 h-7 text-muted-foreground" />
			</div>
			<div class="flex flex-col items-center mx-7">
				<p class="text-xl font-extrabold">956</p>
				<p class="text-sm font-madium">New Orders</p>
			</div>
		</div>
		<div class="flex items-center justify-end rounded-lg border bg-card">
			<div class="border rounded-full p-4">
				<Icon name="heroicons:user" class="w-7 h-7 text-muted-foreground" />
			</div>
			<div class="flex flex-col items-center mx-7">
				<p class="text-xl font-extrabold">5210</p>
				<p class="text-sm font-madium">New Users</p>
			</div>
		</div>
		<div class="flex items-center justify-end rounded-lg border bg-card">
			<div class="border rounded-full p-4">
				<Icon
					name="bi:currency-bitcoin"
					class="w-7 h-7 text-muted-foreground"
				/>
			</div>
			<div class="flex flex-col items-center mx-4">
				<p class="text-xl font-extrabold">20544</p>
				<p class="text-sm font-madium">Unique Visitors</p>
			</div>
		</div>
	</section>
</template>

<script lang="ts" setup></script>

<style></style>
