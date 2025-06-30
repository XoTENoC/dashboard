<template>
	<div class="w-full h-screen grid grid-rows-[50px_1fr_50px] ">
		<div class="w-full h-full flex items-center justify-center p-2 bg-stone-50 border-r-1 border-stone-200">
			<div class="w-full flex flex-row items-center flex-gr gap-2">
				<h1 class="font-bold text-lg uppercase">Nuggslab</h1>
				<Icon
					name="tabler:chevron-down"
					mode="svg"
					size="1.2em"
					class="pointer-events-none aspect-square text-neutral-900 hover:text-black transition-colors duration-150"
				/>
			</div>
		</div>
		<div class="w-full flex flex-col gap-5 p-2 bg-stone-50 border-r-1 border-b-1 border-stone-200 overflow-scroll">
			<div class="flex flex-col gap-2">
				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						iconName="tabler:search"
						iconText="Search"
					/>
				</div>
			</div>

			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					General
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in generalItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>

			<div class="flex flex-col gap-2">
				<h6 class="uppercase text-xs text-neutral-400">
					Settings
				</h6>

				<div class="flex flex-col gap-0.5">
					<AtomsIconItem
						v-for="(item, index) in settingsItems"
						:key="index"
						:iconName="item.iconName"
						:iconText="item.iconText"
						:active="item.active"
					/>
				</div>
			</div>
		</div>
		<div class="w-full h-full bg-stone-100 flex items-center justify-center p-2">
			<div class="w-full flex flex-row items-center flex-gr gap-2 cursor-pointer">
				<div class="h-full flex flex-row grow items-center gap-2">
					<img src="/changiGhibli2.jpg" class="w-8 h-8 rounded-full object-cover" />
					<span class="text-sm text-neutral-800 pointer-events-none">
						Nathaniel Chang
					</span>
				</div>
				<Icon
					name="tabler:dots-vertical"
					mode="svg"
					size="1.2em"
					class="pointer-events-none aspect-square text-neutral-900 hover:text-black transition-colors duration-150"
				/>
			</div>
		</div>
	</div>
</template>

<script setup lang="ts">
const generalItems = [
	{
		iconName: 'tabler:home',
		iconText: 'Dashboard',
		active: false,
	},
	{
		iconName: 'tabler:table-spark',
		iconText: 'Sheets',
		active: false,
	},
	{
		iconName: 'tabler:file-description',
		iconText: 'Files',
		active: false,
	},
	{
		iconName: 'tabler:sticker-2',
		iconText: 'Issues',
		active: false,
	},
	{
		iconName: 'tabler:list-details',
		iconText: 'Forms',
		active: false,
	},
	{
		iconName: 'tabler:photo',
		iconText: 'Photos',
		active: false,
	},
	{
		iconName: 'tabler:question-mark',
		iconText: 'RFIs',
		active: false,
	},
	{
		iconName: 'tabler:clipboard-list',
		iconText: 'Submittals',
		active: true,
	},
	{
		iconName: 'tabler:calendar',
		iconText: 'Meetings',
		active: false,
	},
	{
		iconName: 'tabler:chart-covariate',
		iconText: 'Progress Tracker',
		active: false,
	},
	{
		iconName: 'tabler:calendar-clock',
		iconText: 'Schedule',
		active: false,
	},
	{
		iconName: 'tabler:database',
		iconText: 'Assets',
		active: false,
	},
	{
		iconName: 'tabler:file-delta',
		iconText: 'Reports',
		active: false,
	},
	{
		iconName: 'tabler:users-group',
		iconText: 'Memebers',
		active: false,
	},
];

const settingsItems = [
	{
		iconName: 'tabler:bell-ringing-2',
		iconText: 'Notifications',
		active: false,
	},
	{
		iconName: 'tabler:settings',
		iconText: 'Settings',
		active: false,
	},
	{
		iconName: 'tabler:help',
		iconText: 'Help',
		active: false,
	},
];
</script>