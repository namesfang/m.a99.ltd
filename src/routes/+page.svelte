<script lang="ts">
	export const title = '玖玖记账'
</script>

<h1>{ title }</h1>

<style lang="scss">
	h1 {
		font-size: 1rem;
		&::before {
			content: "";
			border-left: 3px solid #39f;
			padding-left: 10px;
		}
	}
</style>