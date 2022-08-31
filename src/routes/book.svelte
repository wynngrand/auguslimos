<script context="module">
	import { browser, dev } from '$app/env';
	import data from '../data/page.json';
	import Intro from '$lib/home/Intro.svelte';
	export const hydrate = dev;
	export const router = browser;
	export const prerender = true;
</script>

<svelte:head>
	<title>{data.titlebook}</title>
	<meta name="description" content="{data.descbook}"/>
	<link rel="canonical" href="https://www.augustalimoservice.com/book" />
	<!--
			 <title>{data.titlebook}</title> 
<meta content={data.titlebook} property='og:title'/>
<meta content={data.titlebook} name='facebook:title'/>
<meta content={data.titlebook} name='twitter:title'/>
<meta content={data.titlebook} name='keywords'/>
<meta content={data.titlebook} property='og:site_name'/>
<meta content={data.descbook} name="description"/>
<meta content={data.descbook} name='twitter:description'/>
<meta content={data.descbook} name='facebook:description'/>
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
-->
</svelte:head>
<Intro/>
<div class="col-md-12 p-3 text-center">
<h1>{data.titlebook}</h1>
</div>
     <div class="col-md-6 offset-md-3 p-3 p-md-5 mt-3" id="book">
          <iframe id ='booking-frame' width = '100%' frameBorder = '0' src = 'https://account.chauffeurbookingsoftware.com/book/1/123fd7f0-ff6c-4a9d-80fb-05c694c9ed03' style="margin:auto;">
            <p>Your browser does not support iframes.</p>
          </iframe>

          <script src='https://code.jquery.com/jquery-3.3.1.min.js' integrity='sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=' crossorigin='anonymous'></script>

          <script>
          window.addEventListener('message', function(e) {
            var messagePrefix = 'frame height: ';
            var messageScrollPrefix = 'scroll into view: ';

            if (e.data.startsWith(messagePrefix))
            {
              var scrollHeight = e.data.substring(messagePrefix.length);
              scrollHeight = parseInt(scrollHeight);
              var el = document.getElementById('booking-frame');
              var currentHeight = el.style.height;
              if (currentHeight.endsWith('px'))
                currentHeight = currentHeight.substring(0, currentHeight.length - 2);
              if (currentHeight !== scrollHeight)
                el.style.height = scrollHeight + 'px';
            }
            if (e.data.startsWith(messageScrollPrefix)) { scrollElement('#booking-frame'); }
          }, false);

          document.getElementById('booking-frame').focus();

          function scrollElement(jQuerySelector, pixelsFromTop, continueWith)
          {
            if (!pixelsFromTop) pixelsFromTop = 0;
            var navbar = $('header'); //set your header element here
            var navbarHeight = navbar.length === 0 ? 0 : navbar.height(); //or use fixed value like: 250
            var element = $(jQuerySelector);
            if (element.length === 0) return;
            var domElement = element[0];
            if (this.isScrolledIntoView(domElement)) return;
            var offset = $(jQuerySelector).offset();
            $('body,html').animate({ scrollTop: offset.top - pixelsFromTop - navbarHeight, scrollLeft: offset.left }, 500, continueWith);
          }

          function isScrolledIntoView(elem)
          {
            var docViewTop = $(window).scrollTop();
            var docViewBottom = docViewTop + $(window).height();
            var elemTop = $(elem).offset().top;
            var elemBottom = elemTop + $(elem).height();
            return ((elemBottom <= docViewBottom) && (elemTop >= docViewTop));
          }

          </script>
      </div>
