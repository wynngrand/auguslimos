<script context="module">
	import { browser, dev } from '$app/env';
	import data from '../data/page.json';
	import Intro from '$lib/home/Intro.svelte';
	export const hydrate = dev;
	export const router = browser;
	export const prerender = true;
</script>

<svelte:head>
			 <title>{data.titlecontact}</title> 
<meta content={data.titlecontact} property='og:title'/>
<meta content={data.titlecontact} name='facebook:title'/>
<meta content={data.titlecontact} name='twitter:title'/>
<meta content={data.titlecontact} name='keywords'/>
<meta content={data.titlecontact} property='og:site_name'/>
<meta content={data.desccontact} name="description"/>
<meta content={data.desccontact} name='twitter:description'/>
<meta content={data.desccontact} name='facebook:description'/>
<meta content='summary_large_image' name='twitter:card'/>
<meta content='https://twitter.com/hockeycomp' property='twitter:author'/>
<meta content='https://www.facebook.com/mesinkasircomplete' property='facebook:author'/>
<meta content='https://www.youtube.com/c/bakoelraksupermarketMesinKasir' property='youtube:chanel'/>
<meta content='@hockeycomp' name='twitter:site'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='facebook:image'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='twitter:image'/>
<link rel="icon" type="image/x-icon" href="https://github.githubassets.com/favicons/favicon.svg" />
<meta content='https://www.fiverr.com/creativitas' property='og:author'/>
<meta content='website' property='og:type'/>
<meta content='index, follow' name='robots'/>
</svelte:head>
<Intro/>
<div class="col-md-12 p-3 text-center">
<h1>{data.titlecontact}</h1>
</div>
     <div class="col-md-6 offset-md-3 p-3 p-md-5 mt-3" id="book">
       <div class="ratio ratio-16x9">
			 <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d764851.8442962094!2d-87.966415!3d41.510721!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x880e6ec4d30f9fbf%3A0xbc99bcc9134e0c4e!2sNew%20Lenox%2C%20IL!5e0!3m2!1sen!2sus!4v1658854461443!5m2!1sen!2sus" width="600" height="450" style="border:0;" title={data.contact} allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>
      </div>
