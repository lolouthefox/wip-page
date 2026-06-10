<svelte:head>
	<title>Service Unavailable - Homeflix</title>
	<meta name="description" content="Homeflix is currently unavailable. Please check back soon." />
</svelte:head>

<main>
	<div class="maintenance-container">
		<img src="/logo.png" alt="Homeflix Logo" class="logo" />

		<h1>Service Unavailable</h1>
		<p class="message">
			Due to an issue with the hosting company, the media server is currently unavailable. It will
			come back up sometime next month. The new server will feature better performance and
			reliability.
		</p>

		<p class="signature">- Sorry for the inconvenience. -</p>
	</div>
</main>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		font-family: sans-serif;
		background-color: #0a0a0a; /* Deeper, flatter dark background */
		color: #e0e0e0;
		display: flex;
		justify-content: center;
		align-items: center;
		min-height: 100vh;
	}

	main {
		width: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 1rem;
		box-sizing: border-box;
	}

	.maintenance-container {
		max-width: 450px;
		text-align: center;
	}

	.logo {
		height: 4rem;
		margin-bottom: 1rem;
		position: fixed;
		top: 1rem;
		left: 1rem;
	}

	h1 {
		font-size: 1.4rem;
		letter-spacing: 0.5px;
		color: #ffffff;
	}

	.message {
		font-size: 0.95rem;
		line-height: 1.6;
		color: #888888;
	}

	.signature {
		font-size: 0.9rem;
		color: #555555;
		margin: 0;
	}
</style>
