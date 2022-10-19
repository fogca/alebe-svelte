<script>
    import { slide } from 'svelte/transition';
    import Saos from "saos";
    import Logo from './Logo.svelte';
    import Menu from './Menu.svelte';

    let clicked = false;
	let isExpanded = false
	function clickHandler() {
		isExpanded = !isExpanded  
    }
	
</script>

<header class="top">
    <div class="head">
        <Saos animation={"header-logo 1.5s cubic-bezier(0.3, 0, 0.7, 1) both"} once={true}>
            <a href="/" class="logo"><Logo /></a>
        </Saos>
        <Saos animation={"header-logo 1.5s cubic-bezier(0.3, 0, 0.7, 1) both"} once={true}>
            <div class="button menu-button h6" 
                class:clicked={clicked} 
                on:click="{() => clicked = !clicked}"
                on:click|preventDefault={clickHandler}
            >
                <div>Menu</div>
                <span></span>
                <span></span>
            </div>
        </Saos>
        
    </div>
</header>

    {#if isExpanded}
    <Menu />
    {/if}



<style>

@keyframes -global-header-logo {
	0% {transform: translateY(-.25rem);opacity: 0;}
	100% {transform: translateX(0);opacity: 1;}
}


    header {
        width: 100%;
        padding: 4.5rem var(--padding) 0;
        position: absolute;
        top: 0;
        left: 0;
        z-index: 96;
        transition: 2.5s ease-in-out;
        mix-blend-mode: difference;
        filter: contrast(2) brightness(1.5);
    }
    header.top {
        transition: 2.5s ease-in-out;
        mix-blend-mode: normal;
    }
    header .logo {display: block;}
    header .line {
        width: 100vw;
        height: .05px;
        background-color: #aaa;
        opacity: .25;
        margin-left: -5vw;
        margin-top: 1.5rem;
    }

    @media screen and (min-width:720px) {
        
        
        header {
            width: 100%;
            padding: 3.5rem 10vw 0;
        }

        header .line {
            margin-left: -10vw;
            margin-top: 2.5rem;
        }

    }
</style>
