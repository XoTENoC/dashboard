<template>
	<div class="grid grid-cols-[minmax(50px,_300px)_1fr] h-screen max-h-screen overflow-hidden">
		<div class="w-full h-screen overflow-hidden">
			<OrganismSideNav />
		</div>
		<div class="overflow-scroll w-full h-full">
			<slot />
		</div>
	</div>
</template>

<script setup lang="ts">

</script>