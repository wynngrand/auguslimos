<script context="module">
	export const prerender = true;
	import Header from '$lib/home/Header.svelte';
	import Intro from '$lib/home/Intro.svelte';
	import Fleet from '$lib/home/Fleet.svelte';
	import data from '../data/home.json';
</script>


<svelte:head>
	<title>{data.title}</title>
<meta content={data.desc} name='description'/>

</svelte:head>

<section>
<Header/>
<Intro/>
<Fleet/>
</section>
