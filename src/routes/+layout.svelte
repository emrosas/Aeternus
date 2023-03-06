<script>
	import '../app.css';
</script>

<ul>
	<li><a href="/">About Us</a></li>
	<li><a href="/projects">Projects</a></li>
	<li><a href="/pricing">Pricing</a></li>
</ul>

<slot />

<style>
	ul {
		list-style-type: none;
		color: white;
		display: flex;
		gap: 2rem;
	}

	a {
		color: white;
		text-decoration: none;
	}
</style>
