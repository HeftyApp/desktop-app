<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import Logo from '$lib/Logo.svelte';

</script>

<main>
	<Logo />

	<h1 class="bg-red-400">Hello Electron!</h1>

	<Counter id="0" />
</main>

<style style lang="postcss">
	:root {
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
			Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
	}

	:global(body) {
		margin: 0;
		padding: 0;
	}

	main {
		padding: 2em 1em 1em 1em;
		@apply text-center;
		animation: fade 1s;
		@apply mx-auto;
	}

	@keyframes fade {
		from {
			opacity: 0;
		}
		to {
			opacity: 1;
		}
	}

</style>
