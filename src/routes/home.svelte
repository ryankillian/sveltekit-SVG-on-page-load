<script>
	import { goto } from '$app/navigation';

	function gotoSVG() {
		goto('/');
	}
</script>

<h1>Home</h1>
<button on:click={gotoSVG}>Click for intro page</button>

<style>
	button {
		background-color: orange; /* Green */
		border-radius: 12px;
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
	}
</style>
