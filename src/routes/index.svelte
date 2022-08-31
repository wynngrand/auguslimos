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
	<!--
			 <title>{data.title}</title> 
<meta content={data.title} property='og:title'/>
<meta content={data.title} name='facebook:title'/>
<meta content={data.title} name='twitter:title'/>
<meta content={data.title} name='keywords'/>
<meta content={data.title} property='og:site_name'/>
<meta content={data.desc} name="description"/>
<meta content={data.desc} name='twitter:description'/>
<meta content={data.desc} name='facebook:description'/>
<meta content='summary_large_image' name='twitter:card'/>
<meta content='https://twitter.com/hockeycomp' property='twitter:author'/>
<meta content='https://www.facebook.com/mesinkasircomplete' property='facebook:author'/>
<meta content='https://www.youtube.com/c/bakoelraksupermarketMesinKasir' property='youtube:chanel'/>
<meta content='@hockeycomp' name='twitter:site'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='facebook:image'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='twitter:image'/>
<link rel="icon" type="image/x-icon" href="https://github.githubassets.com/favicons/favicon.svg" />
<meta content='Mesin Kasir' property='og:author'/>
<meta content='website' property='og:type'/>
<meta content='index, follow' name='robots'/>
-->
</svelte:head>

<section>
<Header/>
<Intro/>
<Fleet/>
</section>
