<script>
	import Arrow from '../../components/Arrow.svelte';
    import Logo from '../../components/Logo.svelte';
	import Saos from "saos";
    import { MetaTags } from 'svelte-meta-tags';
</script>

<svelte:head>
	<title>Contact | ALEBE - Vintage Curation Studio</title>
</svelte:head>


<MetaTags
  title="Contact | ALEBE - Vintage Curation Boutique"
  description="日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。"
  canonical="https://www.canonical.ie/"
  openGraph={{
    url: 'https://alebe.jp/contact/',
    title: 'Contact | ALEBE - Vintage Curation Boutique',
    description: '日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。',
    images: [
      {
        url: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
        width: 800,
        height: 600,
        alt: 'ALEBE Key Visual'
      }
    ],
    site_name: 'ALEBE | Vintage Curation Boutique'
  }}
  twitter={{
    handle: '@handle',
    site: '@site',
    title: 'Contact | ALEBE - Vintage Curation Boutique',
    description: '日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。',
    image: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
    imageAlt: 'Twitter image alt'
  }}
/>


<main class="page dark-mode">
	<section id="contact-top" class="page-top">
        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
        <h1 class="h0" lang="en">Contact</h1></Saos>
        <Saos animation={"body 1.25s .3s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
		<img src="../image/kv.webp" alt="contact-img" class="l-right-img"></Saos>
        <a href="/" class="h2" lang="en">Get in Touch</a>
	</section>
                
    <section id="contact-press">
        <div class="l-headings">
            <Saos animation={"body 1.25s .3s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h1 class="h5" lang="en">Identity</h1></Saos>
            <Saos animation={"body 1.25s .4s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h2 class="h0" lang="en">Press Kit - <br>Words & Visuals</h2></Saos>
        </div>

        <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>プロフィールテキストやブランドビジュアル等<br>必要な方はこちらをご活用ください。</p>
        </Saos>
        <div class="wrapper">
            <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
                <div class="l-line"></div>
                <h3 class="h3">プロフィールテキスト</h3>
                <p class="h5">日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。</p>
                <div class="l-line"></div>
            </Saos>
            <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="container">
                <img src="../image/kv.webp" alt="contact-img" class="">
                <h4 class="h5">キービジュアル</h4>
            </div></Saos>
            <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="container">
                <img src="../image/kv.webp" alt="contact-img" class="">
                <h4 class="h5">キービジュアル</h4>
            </div></Saos>
            <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="container">
                <img src="../image/kv.webp" alt="contact-img" class="">
                <h4 class="h5">キービジュアル</h4>
            </div></Saos>

        </div>
    </section>




</main>


<style>
	@keyframes -global-scroll-animation {0% {transform: translateY(1.5rem);opacity: 0;}100% {transform: translateY(0);opacity: 1;}}
    @keyframes -global-body {
        0% {transform: translateY(.5rem);opacity: 0;}
        100% {transform: translateY(0);opacity: 1;}
    }
    
    #contact-press {
        padding-top: 8rem;
        padding-bottom: 4rem;
    }

    #contact-press .l-line {
        width: 100%;
        margin: 4rem 0;
    }

    #contact-press .container {margin-bottom: 4rem;}
    #contact-press .container img {aspect-ratio: 3/2;}
	
</style>