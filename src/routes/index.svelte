<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import Menu from '$lib/Menu.svelte';
</script>

<main>
	<h1>
		<span>death</span><span class="pink">Metta</span>
	</h1>

	

	<Counter />

	<p>Welcome to deathMetta.</p>

	<Menu />

</main>

<style>
	main {
		color: white;
		text-align: center;
		/* padding: 1em; */
		margin: 0 auto;
		overflow: hidden;
	}
	h1 {
		font-size: 2rem;
		font-weight: 100;
		line-height: 1.1;
		margin: .5rem auto;
		margin-top: 0;
		max-width: 14rem;
	}



	@media (min-width: 480px) {
		h1 {
			max-width: none;
		}
	}
	.pink {
		color: pink;
		font-style: italic;
		font-weight: bold;
	}	
</style>
