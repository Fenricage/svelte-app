<script>
	let counter = 1;

	const handleClick = () => counter++;
</script>

<h1>Couter:, {counter}!</h1>
<button on:click={handleClick}>Increment counter</button>
