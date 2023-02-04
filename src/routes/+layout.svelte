<script>
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
</script>

<svelte:head>
	<title>Michée Allidjinou</title>
	<meta name="description" content="Made with Sveltekit 1.0" />
</svelte:head>

<div class="flex flex-col items-center min-h-screen bg-slate-300">
	<div class="flex flex-col min-h-screen lg:w-3/4 w-screen bg-green-200 px-8">
		<Navbar />
		<slot />
	</div>
</div>
