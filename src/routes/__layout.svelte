<script>
	import Nav from '$components/Nav.svelte';
</script>

<Nav />
<div>
	<slot />
</div>

<style>
	div {
		display: grid;
		place-items: center;
	}
</style>
