<script>
		import RoomNav from '$lib/components/roomNav/roomNav.svelte';
</script>

<svelte:head>
	<title>EMMETT THOMPSON</title>
	<meta name="description" content="Neuroscientist" />
</svelte:head>

<!-- <section>
	<RoomNav selected="lobby" scale=".85" type="lobby" />
</section> -->

<style>
	section {
		margin: auto 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		/* background: var(--background); */
		max-height: 500px;
		max-width: 100%;
	}

	h1 {
		width: 100%;
		color: var(--primary);
		font-family: var(--font-header);
	}

</style>
