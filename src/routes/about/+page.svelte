<script>
	import Arrow from '../../components/Arrow.svelte';
    import Logo from '../../components/Logo.svelte';
	import Saos from "saos";
    import { MetaTags } from 'svelte-meta-tags';
</script>

<svelte:head>
	<title>About Us | ALEBE - Vintage Curation Boutique</title>
</svelte:head>

<MetaTags
  title="About Us | ALEBE - Vintage Curation Boutique"
  description="日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。"
  canonical="https://alebe.jp/about/"
  openGraph={{
    url: 'https://alebe.jp/about/',
    title: 'About Us | ALEBE - Vintage Curation Boutique',
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
    title: 'About Us | ALEBE - Vintage Curation Boutique',
    description: '日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。',
    image: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
    imageAlt: 'Twitter image alt'
  }}
/>

<main class="page dark-mode">
	<section id="about-top" class="page-top">
        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
        <h1 class="h0" lang="en">About Us</h1></Saos>
        <Saos animation={"body 1.25s .3s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
		<img src="../image/kv.webp" alt="about-img" class="l-right-img"></Saos>
	</section>

    <section id="about-identity">
        <div class="l-headings">
            <Saos animation={"body 1.25s .3s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h1 class="h5" lang="en">Identity</h1></Saos>
            <Saos animation={"body 1.25s .4s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h2 class="h0" lang="en">Our Philosophy & <br>Brand Identity</h2></Saos>
        </div>

        <Saos animation={"body 1.25s .5s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>わたしたちは、古物を扱います。<br>
                サステナビリティやヴィンテージの風潮など<br>
                時代により古物の印象は変わりつつあります。<br><br>
                
                ただ、その本質としては、古きに敬意を払い<br>
                愛情をもって、伝え、残すことです。<br>
                先人が想い、考え、作ったものを<br>
                受け継ぎ、また大切に繋いでいく。<br><br>
                
                そういったバトンリレーが、<br>
                至極当然かのような世界をー、<br>
                敬意と愛情に溢れた素敵な社会を目指してー。<br><br>
                
                アルべは、ドイツ語で「年」や「古き」を意味する<br>
                「Alt」と、「伝える」や「継承する」を意味する<br>
                「Erben」から成る、わたしたちの想いを表した<br>
                大切な言葉です。
            </p>
        </Saos>

        <Logo />
    </section>


    <section id="about-stores">
        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
        <img src="../image/kv.webp" alt="about-img" class="l-right-img"></Saos>
        <div class="l-headings">
            <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h1 class="h5" lang="en">Experience</h1></Saos>
            <Saos animation={"body 1.25s .15s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h2 class="h0" lang="en">Stores you can <br>See and touch</h2></Saos>
        </div>

        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>わたしたちの想いに共感していただき<br>
                アイテムをお取り扱いしていただいています。</p>
        </Saos>
        <div class="l-links">
            <Saos animation={"body 1.25s .30s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="l-line"></div>
            <a href="#a">
                <div class="h3" lang="en">Coming Soon</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>
            <Saos animation={"body 1.25s .40s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <a href="#a">
                <div class="h3" lang="en">Coming Soon</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>
        </div>
    </section>

</main>


<style>
	@keyframes -global-scroll-animation {0% {transform: translateY(1.5rem);opacity: 0;}100% {transform: translateY(0);opacity: 1;}}
    @keyframes -global-body {
        0% {transform: translateY(.5rem);opacity: 0;}
        100% {transform: translateY(0);opacity: 1;}
    }
    
    
    #about-identity {padding-top: 3rem;}
    #about-identity p {
        font-size: 1.35rem;
        letter-spacing: .1em;
        margin-bottom: 6rem;
    }

    #about-stores {padding-top: 10rem;}
    #about-stores .l-links a {padding: 2rem .15rem 1.8rem .5rem;}
    #about-stores .l-line {width: calc( 100vw - (var(--padding) * 2) );}
	
</style>