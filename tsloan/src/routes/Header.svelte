<script lang="ts">
	import { resolve } from '$app/paths';
	import { page } from '$app/state';
	import github from '$lib/images/github.svg';
	import logo from '$lib/images/svelte-logo.svg';
</script>

<header>
	<h1>TSloan</h1>
	<nav>
		<ul>
			<li aria-current={page.url.pathname === '/' ? 'page' : undefined}>
				<a href={resolve('/')}>Home</a>
			</li>
			<li aria-current={page.url.pathname === '/news' ? 'page' : undefined}>
				<a href={resolve('/news')}>News</a>
			</li>
			<li aria-current={page.url.pathname.startsWith('/learn') ? 'page' : undefined}>
				<a href={resolve('/learn')}>Learn</a>
			</li>
			<li aria-current={page.url.pathname === '/about' ? 'page' : undefined}>
				<a href={resolve('/about')}>About</a>
			</li>
		</ul>
	</nav>
</header>

<style>
	header {
		h1 {
			font-family: var(--font-body);
			font-size: 4rem;
			margin: 2rem;
		}
		nav {
			border-top: 2px solid var(--color-theme-2);
			border-bottom: 2px solid var(--color-theme-2);
			ul {
				position: relative;
				padding: 0;
				margin: 0;
				height: 3em;
				display: flex;
				justify-content: center;
				align-items: center;
				list-style: none;
				background-size: contain;
				li {
					position: relative;
					height: 100%;
					a {
						display: flex;
						height: 100%;
						align-items: center;
						padding: 0 0.5rem;
						color: var(--color-text);
						font-weight: 700;
						font-size: 0.8rem;
						text-transform: uppercase;
						letter-spacing: 0.1em;
						text-decoration: none;
						transition: color 0.2s linear;
						&:hover {
							color: var(--color-theme-1);
						}
					}
					&[aria-current='page']::before {
						--size: 12px;
						content: '';
						width: 0;
						height: 0;
						position: absolute;
						top: 0;
						left: calc(50% - var(--size));
						border: var(--size) solid transparent;
						border-top: var(--size) solid var(--color-theme-2);
					}
				}
			}
		}
	}
</style>
