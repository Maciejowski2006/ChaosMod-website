<nav>
	<em>Chaos Mod</em>
	<div class="nav__links">
		<a href="https://github.com/Maciejowski2006/SCPSL_ChaosMod/" target="_blank">Source Code</a>
		<a href="https://github.com/Maciejowski2006/SCPSL_ChaosMod/releases" target="_blank">Download</a>
	</div>
</nav>

<style lang="scss">
	@use '../styles/utilities';
	@use '../styles/global';

	nav {
		box-sizing: border-box;
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		height: 4rem;
		padding-inline: 6rem;
		background-color: utilities.$grey;
	}
	.nav__links {
		display: flex;
		gap: 2rem;
		font-size: 1.25rem;
	}
	em {
		font-size: 1.5rem;
		font-style: normal;
		color: utilities.$primary;
	}
	a, a:hover, a:visited {
		color: utilities.$white;
		text-decoration: none;
	}
</style>
