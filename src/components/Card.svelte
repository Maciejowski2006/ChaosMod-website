<section>
	<slot />
</section>

<style lang="scss">
	@use '../styles/utilities';
	@use '../styles/global';

	section {
		height: calc(50vh - 4rem);
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		font-size: 1.25rem;
	}
</style>
