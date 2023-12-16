<script>
	const test = $state({ value: 42 });
	$effect(() => {
		console.log("matches", test);
	});

	setTimeout(() => {
		test.value = 55;
	}, 1000);
</script>

<h1>Welcome to SvelteKit</h1>
<p>
	Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
