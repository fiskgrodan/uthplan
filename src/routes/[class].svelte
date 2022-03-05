<script>
	import { page } from '$app/stores';
</script>

<svelte:head>
	<title>Uthplan {$page.params.class}</title>
</svelte:head>

<main>
	<div class="classname">{$page.params.class}</div>
</main>

<style>
	main {
		width: 1000px;
		margin: auto;
		padding-top: 20px;
	}

	.classname {
		text-transform: capitalize;
	}
</style>
