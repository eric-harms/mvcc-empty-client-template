<!--#script-->

<script>
	import { Route, Router } from "svelte-routing";
	import Home from "./routes/home/Home.svelte";
	export let url = "";
</script>

<!--#content-->

<Router {url}>
	<div>
		<Route path="/">
	        <Home />
		</Route>
	</div>
</Router>
