<script>
	import 'tailwindcss/tailwind.css';
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<Nav />
<slot />
<Footer />
