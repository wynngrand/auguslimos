<script>
	import Widget from '$lib/widget/Navbar.svelte';
	import Contact from '$lib/widget/Contact.svelte';
	import data from '../data/widget.json';
	import '../app.css';
</script>

<div class="container-fluid">
<Widget />
<main>
	<slot />
<Contact/>
</main>
</div>
