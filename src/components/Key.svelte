<script>
	export let letter = '';
</script>

<span>{letter}</span>

<style>
	span {
		display: inline-block;
		background: #557bbc;
		color: #fed403;
		min-width: 2em;
		min-height: 2em;
		padding: 0.5em;
		padding-bottom: 0em;
		padding-top: 0.5em;
		margin: 0.25em;
		border-radius: 0.5em;
		font-size: 150%;
		cursor: pointer;
        /* vertical-align: middle; */
        box-shadow: 0 0 0.25em black;
        border: 1px solid black;
        text-transform: uppercase;
        font-weight: bold;
        text-shadow: 0 0 0.25em black;
	}
</style>
