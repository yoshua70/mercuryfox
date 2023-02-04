<script>
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
</script>

<svelte:head>
	<title>Michée Allidjinou</title>
	<meta name="description" content="Made with Sveltekit 1.0" />
</svelte:head>

<div class="flex flex-col min-h-full">
	<Navbar />
	<slot />
</div>
