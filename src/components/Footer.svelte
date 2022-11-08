<script>
import Logo from './Logo.svelte';
import Instagram from './Instagram.svelte';
</script>

<footer>
    <div class="l-line"></div>
    <div class="footer-logo">
        <Logo />
    </div>
    <p class="message">
        わたしたちアルべは、古物を扱う者として、<br>
        古きに敬意を払い、愛情をもって、各アイテムを<br>
        皆様のもとへお届けいたします。<br>
        <br>
        また「衣住食」と「古き」をテーマに<br>
        あらゆるモノ・コトへの造詣を、<br>
        皆様と一緒に深めていければと思います。
    </p>
    
    <ul class="links">
        <li><a href="https://store.alebe.jp/" target="blank_">
            <h2 lang="en" class="h1">Products</h2>
            <h3 class="h6">オンラインストアよりご覧いただけます</h3>
        </a></li>
        <li><a href="/about">
            <h2 lang="en" class="h1">About Us</h2>
            <h3 class="h6">わたしたちの想いと古物への姿勢</h3>
        </a></li>
        <li><a href="/contact">
            <h2 lang="en" class="h1">Contact</h2>
            <h3 class="h6">メールよりお問い合わせください</h3>
        </a></li>
        <li><a href="/contact#contact-press">
            <h2 lang="en" class="h1">Press Kit</h2>
            <h3 class="h6">プレスキットをご用意しております</h3>
        </a></li>
    </ul>
    <div class="instagram">
        <a href="https://www.instagram.com/___.hata/" target="blank_" class="founder">
            <h4 lang="en" class="h5">Founder / Curator</h4>
            <h5 lang="en" class="h4"><Instagram />Hata Shiori</h5>
        </a>
        <a href="https://www.instagram.com/takumiisobe_/" target="blank_" class="founder">
            <h4 lang="en" class="h5">Creative Director</h4>
            <h5 lang="en" class="h4"><Instagram />Takumi Isobe</h5>
        </a>
    </div>
    <div class="h6 copyright">©2022 ALEBE - Vintage Curation Boutique All Rights Reserved<br> </div>
</footer>


<style>
    footer {
        width: 100vw;
        padding: 7.5rem 0 5rem;
        padding-left: var(--padding);
        background-color: var(--darkColor);
    }
    footer * {
        color: var(--lightColor);
        fill: var(--lightColor);
        -webkit-font-smoothing: antialiased;
    }
    footer .message {font-size: 1.35rem;}
    footer .l-line {
        width: 100vw;
        margin-bottom: 6rem;
        margin-left: calc(var(--padding) * -1);
    }
    .Index footer .l-line {margin: 0;}
    footer .footer-logo {margin-bottom: 5rem;}
    
    footer ul.links {margin: 5rem 0 5rem;}
    footer ul.links li {margin-bottom: 2.5rem;}
    footer ul.links li:nth-of-type(4) {margin-bottom: 0;}
    footer ul.links li a {font-size: 2.4rem;}
    footer ul.links li.contact a {font-size: 1.8rem;}

    footer .instagram a {margin-right: 4rem;}
    footer .instagram a h4 {margin-bottom: .5rem;}

    footer .copyright {margin-top: 3rem;}

    @media screen and (min-width: 720px) {


        footer {
            padding: 0 10vw 5rem;
        }

    }

</style>