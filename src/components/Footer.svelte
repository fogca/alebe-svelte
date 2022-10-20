<script>
import Logo from './Logo.svelte'
</script>

<footer>
    <div class="l-line"></div>
    <div class="footer-logo">
        <Logo />
    </div>
    
    <ul class="links">
        <li><a href="https://store.alebe.jp/" target="blank_">Products →</a></li>
        <li><a href="/about">About Us →</a></li>
        <li><a href="/contact">Contact →</a></li>
        <li><a href="/contact#contact-press">Press Kit →</a></li>

        <li class="contact">
            <div class="h6">Instagram</div>
            <a href="https://www.instagram.com/___.hata/" target="blank_">Curator - Hata Shiori</a>
        </li>
        <li class="contact">
            <div class="h6">Instagram</div>
            <a href="https://www.instagram.com/takumiisobe_/" target="blank_">Director - Takumi Isobe</a>
        </li>
    </ul>
    <div class="h6 copyright">©2022 ALEBE <br>Vintage Curation Boutique<br> </div>
</footer>


<style>
    footer {
        width: 100vw;
        padding: 6rem 0 5rem;
        padding-left: var(--padding);
        background-color: var(--darkColor);
    }
    footer * {
        color: var(--lightColor);
        fill: var(--lightColor);
        -webkit-font-smoothing: antialiased;
    }
    footer .l-line {
        width: 100vw;
        margin-bottom: 6rem;
        margin-left: calc(var(--padding) * -1);
    }
    footer .footer-logo {margin-bottom: 5rem;}
    
    ul {margin-bottom: 12rem;}

    footer ul.links li {margin-bottom: .2rem;}
    footer ul.links li:nth-of-type(4) {margin-bottom: 4rem;}
    footer ul.links li.contact {margin-bottom: 2.4rem;}
    footer ul.links li a {font-size: 2.4rem;}
    footer ul.links li.contact a {font-size: 1.8rem;}


    @media screen and (min-width: 720px) {


        footer {
            padding: 0 10vw 5rem;
        }

    }

</style>