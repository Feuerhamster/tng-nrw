<script lang="ts">
	import "@fontsource-variable/lexend";
</script>

<slot />

<style lang="scss">
	@import "../scss/colors.scss";

	:global(html) {
		font-size: 18px;
		font-family: "Lexend Variable", sans-serif;
		color: var(--color-text);
		font-weight: 400;
	}

	:global(body) {
		background-color: var(--color-bg);
		display: flex;
		flex-direction: column;
		height: 100vh;
		margin: 0;
	}
		
</style>