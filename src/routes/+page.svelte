<script>
	import Arrow from '../components/Arrow.svelte';
	import Saos from "saos";
    import { MetaTags } from 'svelte-meta-tags';
</script>

<svelte:head>
	<title>ALEBE | Vintage Curation Boutique</title>
</svelte:head>

<MetaTags
  title="ALEBE | Vintage Curation Boutique"
  description="日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。"
  canonical="https://alebe.jp/"
  openGraph={{
    url: 'https://alebe.jp/',
    title: 'Vintage Curation Boutique',
    description: '日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。',
    images: [
      {
        url: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
        width: 800,
        height: 600,
        alt: 'ALEBE Key Visual'
      },
      {
        url: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
        width: 900,
        height: 800,
        alt: 'ALEBE Key Visual'
      }
    ],
    site_name: 'ALEBE | Vintage Curation Boutique'
  }}
  twitter={{
    handle: '@handle',
    site: '@site',
    cardType: 'summary_large_image',
    title: 'ALEBE | Vintage Curation Boutique',
    description: '日々の生活にエッセンスを与えるヴィンテージブランド、ALEBE。欧州を中心にキュレーションされたアイテムは、グラスやカトラリーといったテーブルウェアから、アクセサリーやオブジェクトまで多岐にわたり、日々を彩る。古きに敬意を払い、愛情をもって、受け継ぎ、繋いでいくことをブランドの核なる想いとし、古物と真摯に向き合い、アイテムを届けている。',
    image: 'https://www.alebe-svelte.pages.dev/images/alebe_kv.JPG',
    imageAlt: 'Twitter image alt'
  }}
  facebook={{
    appId: '1234567890'
  }}
/>

<main>
	<section id="index-top" class="l-full-img">
		<Saos animation={"opening-img 3.0s cubic-bezier(0.65, 0, 0.35, 1) both"} once={true}>
			<img src="../image/alebe_kv.JPG" alt="" class="kv">
		</Saos>

        <div class="texts">
            <Saos animation={"body 1.8s 1.2s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
                <div class="container">欧米諸国を中心に中世から近世にかけて製造されたアイテムをキュレーション。日々の生活に<br>エッセンスを加えるアイコニックなオブジェクトやテーブルウェア、アクセサリーを扱っております。</div>
            </Saos>
        </div>
        <div class="scroll h3" lang="en">
            <Saos animation={"body 1.8s 1.7s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}><div class="container">Scroll Down</div></Saos>
        </div>
        <div class="shop h2" lang="en">
            <Saos animation={"body 1.8s 2.2s cubic-bezier(.75, 0, 0.25, 1) both"} once={true}><a href="https://store.alebe.jp/" target="blank_" class="container">Shop Now</a></Saos>
        </div>

	</section>

    <section id="index-concept">
        <div class="l-headings">
            <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
                <h1 class="h5" lang="en">Concept</h1>
            </Saos>
            <Saos animation={"body 1.25s .15s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
                <h2 class="h0" lang="en">Middle Ages to <br>early modern times</h2>
            </Saos>
        </div>
        <Saos animation={"body 1.25s .30s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>欧米諸国を中心に中世から近世にかけて製造された<br>
                アイテムをキュレーション。日々の生活に<br>
                エッセンスを加えるアイコニックなオブジェクトや<br>
                テーブルウェア、アクセサリーを扱っております。</p>
        </Saos>
        <div class="l-links">
            <Saos animation={"body 1.25s .30s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="l-line"></div>
            <a href="/about">
                <div class="h2" lang="en">About Us</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>
            <Saos animation={"body 1.25s .40s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <a href="/contact#contact-press">
                <div class="h2" lang="en">Press Kit</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>
        </div>
    </section>


    <section id="index-products">
        <div class="l-headings">
            <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h1 class="h5" lang="en">Products</h1></Saos>
            <Saos animation={"body 1.25s .15s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h2 class="h0" lang="en">We Offer a variety of <br>Lifestyle Vintage items</h2></Saos>
        </div>

        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>皆んなで囲む食卓に彩りをはこぶテーブルウェアや、<br>
                暮らしの空間に、アクセントを与えるオブジェクト、<br>
                お出かけの装いに華を添えるジュエリーなど、<br>
                衣食住の幸せに寄り添う様々な古物を扱っております。</p>
        </Saos>
        <div class="l-banners">
            <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <a href="https://store.alebe.jp/collections/glassware" target="blank_">
                <div class="l-white">
                    <h3 class="h1" lang="en">Tableware</h3>
                    <h4 class="h6">陶磁器やカトラリーなどのテーブルアイテム</h4>
                </div>
                <Arrow />
            </a>
            </Saos>
            <Saos animation={"body 1.25s .3s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <a href="https://store.alebe.jp/collections/accessory" target="blank_">
                <div class="l-white">
                    <h3 class="h1" lang="en">Accessory</h3>
                    <h4 class="h6">ネックレスやピアスなどの宝飾品</h4>
                </div>
                <Arrow />
            </a>
            </Saos>
        </div>
    </section>

    <section id="index-gallery">
        <div class="l-headings">
            <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h1 class="h5" lang="en">Gallery</h1></Saos>
            <Saos animation={"body 1.25s .15s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <h2 class="h0" lang="en">
                Harmony created <br>when vintage cross <br>over modern lives</h2></Saos>
        </div>
        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <p>ヴィンテージアイテムが現代の生活と<br>
                交り合い、溶けこむで、もたらす独特の調和や彩り</p>
        </Saos>
        <Saos animation={"body 1.25s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
        <div class="wrapper">
            <img src="../image/kv.webp" alt="">
            <img src="../image/menu.webp" alt="">
            <img src="../image/menu.webp" alt="">
            <img src="../image/kv.webp" alt="">
        </div>
        </Saos>
    </section>

    
    <section id="index-news">
        <div class="l-headings">
            <h1 class="h5" lang="en">News</h1>
            <h2 class="h0" lang="en">Information about <br>Collection & Pop-Up</h2>
        </div>
        <p>コレクションや <br>ポップアップに関するお知らせ</p>
        <div class="l-links">

            <Saos animation={"body 1.25s .30s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <div class="l-line"></div>
            <a href="#index-news">
                <div class="h2" lang="en">Coming Soon</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>

            <Saos animation={"body 1.25s .40s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
            <a href="#index-news">
                <div class="h2" lang="en">Coming Soon</div>
                <Arrow />
            </a>
            <div class="l-line"></div>
            </Saos>

            <Saos animation={"body 1.25s .40s cubic-bezier(.75, 0, 0.5, 1) both"} once={true}>
                <a href="#index-news">
                    <div class="h2" lang="en">Coming Soon</div>
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
    @keyframes -global-opening-img {
        0% {opacity: 0;height: 100%;}
        100% {opacity: 1;height: 100%;}
    }

    #index-top {height: 100vh;}
    #index-concept {padding-top: 6rem;}
    #index-products, #index-gallery,
    #index-news {padding-top: 8rem;}


    #index-top {
        position: relative;
        height: 100vh;
        height: 100svh;
    }
    #index-top .kv {height: 100svh; height: 100vh;}
    #index-top .shop, #index-top .scroll {height: fit-content;}
    #index-top .shop, #index-top .scroll, #index-top .texts {position: absolute;}
    #index-top .shop {
        top: auto;left: auto;
        bottom: 0;right: 0;
    }
    #index-top .shop .container {
        padding: 2rem 4rem;
        background-color: var(--lightColor);
    }
    #index-top .texts {
        top: 8rem;
        left: calc(100% - var(--padding) - 3.8rem);
        height: 90vh;
    }
    #index-top .texts .container {
        color: var(--lightColor);
        letter-spacing: .15em;
        writing-mode: vertical-rl;
        font-feature-settings: initial;
    }
    #index-top .scroll {
        top: auto;
        bottom: 7rem;
        left: var(--padding);
    }
    #index-top .scroll .container {
        color: var(--lightColor);
        white-space: nowrap;
        writing-mode: vertical-rl;
        font-feature-settings: initial;
    }






    #index-products .l-banners {margin-top: 4rem;}

    #index-gallery .wrapper {
        width: 100vw;
        margin-top: 4rem;
        display: flex;
        flex-wrap: wrap;
        align-items: flex-start;
        justify-content: space-between;
        margin-left: calc( var(--padding) * -1 );
    }
    #index-gallery .wrapper img {
        width: calc(50vw - 1px);
        margin-bottom: 2px;
    }
    #index-gallery .wrapper img:nth-of-type(1),
    #index-gallery .wrapper img:nth-of-type(4) {height: 60vw;}
    #index-gallery .wrapper img:nth-of-type(2),
    #index-gallery .wrapper img:nth-of-type(3) {height: 40vw;}
    #index-gallery .wrapper img:nth-of-type(4) {margin-top: -20vw;}

    

    @media screen and (min-width: 720px) {

        #index-gallery .wrapper {width: 100%;margin-left: 0;}
        #index-gallery .wrapper img {width: calc(50% - 1px);}
        #index-gallery .wrapper img:nth-of-type(1),
        #index-gallery .wrapper img:nth-of-type(4) {height: 50vh;}
        #index-gallery .wrapper img:nth-of-type(2),
        #index-gallery .wrapper img:nth-of-type(3) {height: 30vh;}
        #index-gallery .wrapper img:nth-of-type(4) {margin-top: -20vh;}
    }


	
</style>