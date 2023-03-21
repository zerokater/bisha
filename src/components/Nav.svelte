<script>
    import { slide } from 'svelte/transition';
    import { quartOut } from 'svelte/easing';

    let open = false;

    function toggle() {
        open = !open;
    }
</script>

<header>
    <a href="/"><h1>bisha.</h1></a>
    
    <nav>
        {#if open}
            <div class="hamburger-open" on:click={toggle} on:keydown|preventDefault={toggle}  transition:slide="{{duration: 500, easing: quartOut}}"></div>
        {:else}
            <svg on:click={toggle} on:keydown|preventDefault={toggle} class="hamburger" height="50" width="50"><path d="M6 36v-3h36v3Zm0-10.5v-3h36v3ZM6 15v-3h36v3Z"/></svg>
        {/if}
        <a href="/projekte">Projekte</a>
        <a class="kontakt" href="/kontakt">Kontakt</a>
    </nav>
</header>

<style>
    header {
        width: 100%;
        height: 10rem;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    nav {
        display: flex;
        gap: 2rem;
        align-items: center;
    }

    a {
        font-weight: 500;
        font-size: 1.6rem;
        text-decoration: none;
        color: black;
        transition: 0.3s color;
    }

    a:hover {
        color: orangered;
    }

    .kontakt {
        background-color: orangered;
        border-radius: 0.5rem;
        color: white;
        padding: 0.5rem;
        border: 2pt solid orangered;
        transition: 0.3s background-color;
    }

    .kontakt:hover {
        background-color: white;
        color: orangered;
    }

    .hamburger {
        cursor: pointer;
        display: none;
        transition: 0.3s fill;
    }

    .hamburger:hover{
        fill: orangered;
    }

    .hamburger-open {
        position: absolute;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100%;
        background-color: orangered;
    }
    

    @media only screen and (max-width: 1120px) {
        nav a {
            display: none;
        }

        .hamburger {
            display: block;
        }
    }

    @media only screen and (max-width: 600px) {
        header {
            height: 7rem;
        }
    }

</style>
