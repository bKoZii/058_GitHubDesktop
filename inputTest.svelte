<script>
	let name = $state('Konkamon');
</script>

<input type="text" bind:value={name} placeholder="Enter Your Name...">
<h1>Hello, {name}!</h1>
