<script lang="ts">
	import IconLink from "./components/IconLink.svelte";
	import LinePainter from "./components/LinePainter.svelte"
</script>

<main>
	<div class="header">
		<h1>
			Hi, I'm Aaron Dov Turkel	
			<div class="links">
				<IconLink href="https://github.com/AaronDovTurkel">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
				</IconLink>
				<IconLink href="https://www.linkedin.com/in/aaron-turkel/">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
				</IconLink>
				<IconLink href="mailto:aarondovturkel@gmail.com?subject=Professional Inquiry">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M23 0l-4.5 16.5-6.097-5.43 5.852-6.175-7.844 5.421-5.411-1.316 18-9zm-11 12.501v5.499l2.193-3.323-2.193-2.176zm-8.698 6.825l-1.439-.507 5.701-5.215 1.436.396-5.698 5.326zm3.262 4.287l-1.323-.565 4.439-4.503 1.32.455-4.436 4.613zm-4.083.387l-1.481-.507 8-7.89 1.437.397-7.956 8z"/></svg>
				</IconLink>
			</div>
		</h1>
		<p>I am a full stack software engineer, that loves tinkering and building scalable structured solutions.</p>
		<div class="links-mobile">
			<IconLink href="https://github.com/AaronDovTurkel">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
			</IconLink>
			<IconLink href="https://www.linkedin.com/in/aaron-turkel/">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
			</IconLink>
			<IconLink href="mailto:aarondovturkel@gmail.com?subject=Professional Inquiry">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M23 0l-4.5 16.5-6.097-5.43 5.852-6.175-7.844 5.421-5.411-1.316 18-9zm-11 12.501v5.499l2.193-3.323-2.193-2.176zm-8.698 6.825l-1.439-.507 5.701-5.215 1.436.396-5.698 5.326zm3.262 4.287l-1.323-.565 4.439-4.503 1.32.455-4.436 4.613zm-4.083.387l-1.481-.507 8-7.89 1.437.397-7.956 8z"/></svg>
			</IconLink>
		</div>
	</div>
	<LinePainter/>
</main>

<style>

	main {
		width: 100%;
		height: 100%;
		overflow: hidden;
		display: grid;
		position: relative;
	}

	h1 {
		color: #ffffff;
		font-size: calc(20px + (52 - 20) * ((100vw - 300px) / (1600 - 300)));
		font-weight: 700;
		margin: 0;
		display: flex;
		column-gap: 15px;
	}

	p {
		font-size: calc(14px + (26 - 14) * ((100vw - 300px) / (1600 - 300)));
		font-weight: 500;
		color: rgb(188, 221, 225);
		margin: 0;
	}

	svg {
		fill: lightgreen;
		background-color: transparent;
		width: calc(14px + (32 - 14) * ((100vw - 300px) / (1600 - 300)));
		height: calc(14px + (32 - 14) * ((100vw - 300px) / (1600 - 300)));
	}

	svg:hover {
		fill:rgb(188, 221, 225);
	}

	.header {
		display: grid;
		row-gap: 10px;
		width: 60vw;
		z-index: 2;
		margin-left: 10%;
		margin-top: -10%;
		align-self: center;
		background-color: #262626;
    	padding: 25px;
    	border-radius: 50px;
	}

	.links-mobile {
		display: none;
	}

	@media (max-width: 1030px) {
		.header {
			margin-left: 0px;
			justify-self: center;
			align-self: center;
		}
		.links {
			display: none;
		}

		.links-mobile {
			display: block;
			justify-self: center;
			padding-top: 20px;
		}
	}
</style>