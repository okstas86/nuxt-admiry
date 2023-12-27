<template>
	<aside class="w-[250px] h-full">
		<div
			class="sticky bg-[#f0f1f4] flex w-full h-full flex-col gap-5 overflow-y-auto rounded-md border bg-card pb-5 scrollbar-thin scrollbar-thumb-input scrollbar-thumb-rounded-md"
		>
			<div
				class="flex items-center justify-center fixed top-0 left-0 w-[250px] h-[100px] mb-5 bg-[#f0f1f4]"
			>
				<h1 class="text-4xl">Admiry</h1>
			</div>
			<div class="flex mt-20 items-center justify-center w-full h-[250px]">
				<div class="flex flex-col m-10">
					<img
						src="https://randomuser.me/api/portraits/med/men/71.jpg"
						alt="Logged in user"
						class="mx-auto w-20 h-20 rounded-full ring-1 ring-border"
					/>
					<div class="flex items-center flex-col mt-5 text-center">
						<h3 class="font-medium">Stanislav Ocunev</h3>
						<div
							class="flex items-center justify-center w-[80px] h-[30px] mt-5 border #bebfc1 rounded-full text-sm"
						>
							Online
						</div>
					</div>
				</div>
			</div>
			<SidebarItem :links="menu" />
			<div class="mt-auto">
				<SidebarItem :links="bottomMenu" />
			</div>
		</div>
	</aside>
</template>

<script setup>
import SidebarItem from '../components/SidebarItem.vue'

const bottomMenu = [
	{
		title: 'Settings',
		icon: 'heroicons:cog-8-tooth',
	},
	{
		title: 'Help',
		icon: 'heroicons:question-mark-circle',
	},
	{
		title: 'Logout',
		icon: 'heroicons:arrow-left-on-rectangle',
	},
]
const menu = [
	{
		title: 'Dashboard',
		icon: 'heroicons:home',
	},
	{
		title: 'User Interface',
		icon: 'heroicons:user-group',
		items: [
			{ title: 'List' },
			{ title: 'Create' },
			{ title: 'Edit' },
			{ title: 'Delete' },
			{ title: 'Details' },
		],
	},
	{
		title: 'Orders',
		icon: 'heroicons:shopping-cart',
		items: [
			{ title: 'List' },
			{ title: 'Create' },
			{ title: 'Edit' },
			{ title: 'Delete' },
			{ title: 'Details' },
		],
	},
	{
		title: 'Products',
		icon: 'heroicons:cube',
		items: [
			{ title: 'List' },
			{ title: 'Create' },
			{ title: 'Edit' },
			{ title: 'Delete' },
			{ title: 'Details' },
		],
	},
	{
		title: 'Staff',
		icon: 'heroicons:user',
		items: [
			{ title: 'List' },
			{ title: 'Create' },
			{ title: 'Edit' },
			{ title: 'Delete' },
			{ title: 'Details' },
		],
	},
	{
		title: 'Analytics',
		icon: 'heroicons:chart-pie',
		items: [
			{ title: 'Overview' },
			{ title: 'Statistics' },
			{ title: 'Trends' },
		],
	},
]
</script>

<style></style>
