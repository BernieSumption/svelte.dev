<script>
	let { children } = $props();
</script>

<nav>
	<a href="/">home</a>
	<a href="/expected">page with expected error</a>
	<a href="/unexpected">page with unexpected error</a>
</nav>

{@render children()}
