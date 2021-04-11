<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<main>
	<h1>
		<span>death</span><span class="pink">Metta</span>
	</h1>


	<Counter />

</main>

<style>
	main {
		color: white;
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}
	h1 {
		font-size: 4rem;
		font-weight: 100;
		line-height: 1.1;
		margin: .5rem auto;
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
