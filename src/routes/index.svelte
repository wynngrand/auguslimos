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
<meta property="og:type" content="website">
<meta property="og:site_name" content={data.title}>
<meta property="og:locale" content="en_US">
<meta property="og:title" content={data.title}>
<meta property="og:description" content={data.desc}>
<meta property="og:image" content="https://www.grandlimousine.com/img/Chrysler-300-Limousine.webp">
<meta property="og:image:alt" content={data.desc}>
<meta property="og:image:width" content="1280">
<meta property="og:image:height" content="640">    
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:title" content="{data.title}">
<meta property="twitter:description" content={data.desc}>
<meta property="twitter:image" content="https://www.grandlimousine.com/img/Chrysler-300-Limousine.webp">
<meta property="twitter:image:alt" content={data.desc}>
</svelte:head>

<section>
<Header/>
<Intro/>
<Fleet/>
</section>
