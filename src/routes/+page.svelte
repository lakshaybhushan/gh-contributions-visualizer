<script lang="ts">
	import { Canvas } from '@threlte/core';
	import Scene from './scene.svelte';
</script>

<svelte:head>
	<title>Lakshay's GC'23</title>
</svelte:head>

<div class="scene">
	<h1>Lakshay's GitHub Contributions in 2023</h1>
	<Canvas>
		<Scene />
	</Canvas>

	<p>
		Made with <a href="https://threlte.xyz/" target="_blank" rel="noopener noreferrer"> Threlte </a>
	</p>
</div>

<style>
	.scene {
		position: absolute;
		inset: 0;
		background-color: hsl(200 10% 10%);
	}

	h1 {
		position: absolute;
		display: flex;
		align-items: center;
		justify-content: center;
		left: 0%;
		right: 0%;
		margin: 0%;
		padding: 1rem;
		background-color: hsl(200 10% 10%);
		z-index: 1000;
		color: white;
		font-size: 3rem;
		font-family:
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			Roboto,
			Oxygen,
			Ubuntu,
			Cantarell,
			'Open Sans',
			'Helvetica Neue',
			sans-serif;
	}

	p {
		position: absolute;
		bottom: 0;
		right: 0;
		left: 0;
		margin: 0%;
		display: flex;
		align-items: center;
		justify-content: center;
		color: white;
		background-color: hsl(200 10% 10%);
		padding: 1rem;
		font-size: 1rem;
		font-family:
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			Roboto,
			Oxygen,
			Ubuntu,
			Cantarell,
			'Open Sans',
			'Helvetica Neue',
			sans-serif;
	}

	a {
		display: inline-block;
		margin-left: 0.25rem;
		color: orangered;
		text-decoration: none;
	}
</style>
