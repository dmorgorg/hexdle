<script>
	import Keyboard from './Keyboard.svelte';
</script>

<main>
	<header>
		<h1>hexdle!</h1>
	</header>
	<section class="playboard">playboard</section>
	<section class='keyboard'><Keyboard /></section>
</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
		background: #fed403;
		height: 100vh;
		padding: 0;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}	
	header {
		border-bottom: 1px solid black;
		color: black;
		background-color: #557bbc;	
		padding: 0.5em;
		letter-spacing: 0.1em;
		box-shadow: 0 0 1em black;
	}
	h1 {
		text-transform: uppercase;
		margin: 0;
		color: #fed403;
		text-shadow: 0 0 0.25em black;
	}
	.playboard {
		border: 3px solid black;
		margin: 1em auto;
	}
	.keyboard {
		margin: 1em auto;
	}
</style>
