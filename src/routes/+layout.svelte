<script>
import { page } from '$app/stores';
import PageTransition from '../components/PageTransition.svelte';  
import Header from '../components/Header.svelte';
import Footer from '../components/Footer.svelte';
import { MetaTags } from 'svelte-meta-tags';

import { afterNavigate, beforeNavigate } from '$app/navigation';


/** @type {import('./$types').LayoutData} */
    export let data;
    $: currentRoute = $page.url.pathname; 
</script>
  
<svelte:head>
  <link rel="stylesheet" href="../css/base.css?ver=1.0.1">
  <link rel="stylesheet" href="../css/main.css?ver=1.0.1">
  <link rel="stylesheet" href="../css/layout.css?ver=1.0.1">
  <link rel="stylesheet" href="https://use.typekit.net/frp6udl.css">
  <script>
    (function(d) {
      var config = {
        kitId: 'pxy4fzb',
        scriptTimeout: 3000,
        async: true
      },
      h=d.documentElement,t=setTimeout(function(){h.className=h.className.replace(/\bwf-loading\b/g,"")+" wf-inactive";},config.scriptTimeout),tk=d.createElement("script"),f=false,s=d.getElementsByTagName("script")[0],a;h.className+=" wf-loading";tk.src='https://use.typekit.net/'+config.kitId+'.js';tk.async=true;tk.onload=tk.onreadystatechange=function(){a=this.readyState;if(f||a&&a!="complete"&&a!="loaded")return;f=true;clearTimeout(t);try{Typekit.load(config)}catch(e){}};s.parentNode.insertBefore(tk,s)
    })(document);
  </script>
</svelte:head>
  
  <div 
    class:Index={currentRoute === "/"} 
    class:About={currentRoute === "/about"} 
    class:Contact={currentRoute === "/contact"}
  >

  <!-- 2. Pass the `url` prop to the `PageTransition` component, causing it to re-render when the page changes -->
  <PageTransition pathname={data.pathname}>
    <Header></Header>
      <slot />
    <Footer></Footer>
  </PageTransition>
  
  </div>
  