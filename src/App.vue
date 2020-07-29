<template>
  <div id="app">
    <Simon />
  </div>
</template>

<script>
	import Simon from '@/components/Simon';

	export default {
		name: 'App',
		components: {
			Simon,
		},
	};
</script>

<style>
	* {
		box-sizing: border-box;
	}

	html {
		color: var(--font-color);
		font-size: 16px;
		font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	}

	body {
		padding: 0;
		margin: 0;
	}

	:root {
		--font-color: hsl(0, 0%, 21%);
		--heading-color: hsl(0, 0%, 4%);
		--red-color: hsl(6, 78%, 62%);
		--red-color-active: hsl(6, 78%, 57%);
		--red-color-hover: hsl(6, 78%, 52%);
		--blue-color: hsl(204, 70%, 58%);
		--blue-color-active: hsl(204, 70%, 53%);
		--blue-color-hover: hsl(204, 70%, 48%);
		--yellow-color: hsl(48, 89%, 55%);
		--yellow-color-active: hsl(48, 89%, 50%);
		--yellow-color-hover: hsl(48, 89%, 45%);
		--green-color: hsl(145, 63%, 54%);
		--green-color-active: hsl(145, 63%, 49%);
		--green-color-hover: hsl(145, 63%, 44%);

		--smartphone-min-width: 320px;
		--smartphone-max-width: 480px;
		--tablet-min-width: 768px;
		--tablet-max-width: 1024px;
		--desktop-min-width: 1224px;
		--large-screen-min-width: 1824px;
	}

	#app {
		display: flex;
		justify-content: center;
		align-items: center;
		min-height: 100vh;
    padding: 30px;
	}
</style>
