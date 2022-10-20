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
  <title>ALEBE - Vintage Curation Studio</title>
  <meta content="日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。" name="description">
  <meta charset="utf-8">
  <meta property="og:title" content="ページの タイトル" />
  <meta property="og:description" content="ページのディスクリプション" />
  <meta property="og:type" content="ページの種類" />
  <meta property="og:url" content="ページの URL" />
  <meta property="og:image" content="サムネイル画像の URL" />
  <meta property="og:site_name" content="サイト名" />
  <meta property="og:locale" content="ja_JP"  />

  <link rel="stylesheet" href="../css/base.css">
  <link rel="stylesheet" href="../css/main.css">
  <link rel="stylesheet" href="../css/layout.css">
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
  