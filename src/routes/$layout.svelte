<svelte:head>	
	<title>Megaton 0.0.1</title>
</svelte:head>

<script>
	import '../app.css';
	console.log("Pet project. :) Enjoy.")
	import Menu from '$lib/Menu.svelte';
	import Header from '$lib/Header.svelte';

</script>

<main>
	<Header />
	<slot />
	<Menu />
</main>


<style>
	
</style>
