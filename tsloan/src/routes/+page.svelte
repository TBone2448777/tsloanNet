<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>Welcome!</h1>
	<p>
		My name is Taylor Sloan. I created this website for two reasons:
	</p>
	<ol>
		<li>Serving as my form of social media to keep in touch with friends and family (News)</li>
		<li>Creating tutorials and guides for a variety of reasons that I can send to friends and family (Learn)</li>
	</ol>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		flex: 0.6;
		width: 100%;
	}

	h1 {
		width: 100%;
	}

	p, ol {
		margin: 0.4em;
	}
</style>
