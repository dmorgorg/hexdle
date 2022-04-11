<script>
	import { KEYS, COLS } from '../utils.js';
	import Key from './Key.svelte';
</script>

{#each KEYS as row, i}
	<div class='row'>
		{#if i == 2}
			<Key letter='ENTER' />
		{/if}
		{#each row as letter}
			<Key {letter} />
		{/each}
		{#if i == 2}
			<Key letter='BACKSPACE' />
		{/if}
	</div>
	
{/each}

<!-- <style>
	.row {
		border: 2px solid green;
	}
</style> -->



