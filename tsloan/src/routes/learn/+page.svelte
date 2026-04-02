<script lang="ts">
	import { resolve } from '$app/paths';
</script>

<svelte:head>
	<title>Learn</title>
	<meta name="description" content="About this app" />
</svelte:head>

<ul>
	<li>Essential Tech
		<ul>
			<li>Brave Browser</li>
			<li>Bitwarden Password Manager</li>
			<li>uBlock Origin</li>
		</ul>
	</li>
	<li>Piracy Tutorials
		<ul>
			<li><a href={resolve('/learn/stremio')}>Stremio - Replace Every Streaming Service</a></li>
			<li><a href={resolve('/learn/freebooks')}>Free Books for Kindles or other E-Readers</a></li>
			<li>Free Audiobooks</li>
			<li>Free Games</li>
			<li>Ad Free YouTube</li>
			<li><a href={resolve('/learn/realdebrid')}>Real Debrid - Torrenting Made Safe</a></li>
		</ul>
	</li>
	<li>Professional
		<ul>
			<li>Resumes</li>
			<li>Point a Custom Web Domain</li>
		</ul>
	</li>
	<li>Media Essentials
		<ul>
			<li>Over-the-top amazing "TV Speakers"</li>
			<li><a href={resolve('/learn/stremio')}>Stremio - Replace Every Streaming Service</a></li>
		</ul>
	</li>
</ul>

<style>

</style>