<script lang="ts">
	let count = 0;

	const increment = (): void => {
		count += 1;
	};
</script>

<button on:click={increment}>
	Clicks: {count}
</button>

<style lang="scss">
	button {
		font-family: inherit;
		font-size: inherit;
		padding: 1em 2em;
		color: #2c2c2c;
		background-color: yellow;
		border-radius: 2em;
		outline: none;
		width: 200px;
		height: 60px;
		font-variant-numeric: tabular-nums;
</style>
