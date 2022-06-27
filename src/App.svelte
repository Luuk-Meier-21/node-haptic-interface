
<script lang="ts">
	import { Router, Route, Link } from "svelte-routing";

	export let url = "";
</script>

<div>
	<Router url={url}>
		
	</Router>
</div>

<style lang="scss">
  	@import "./static/core/global";
	@import "./static/protons";
	@import "./static/atoms";
</style>
