<script>
    import { slide } from 'svelte/transition';
    import { quartOut } from 'svelte/easing';

    let open = false;

    function toggle() {
        open = !open;
    }
</script>


<div class="aufbau">
    <h1>bisha.</h1>
    <h2>Die Website befindet sich derzeit im Aufbau.</h2>
    <a class="mail" href="mailto:info@bisha.ch">info@bisha.ch</a>
</div>




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

    .aufbau{
        position: absolute;
        top: 0;
        left: 0;
        background-color: orangered;
        display: flex;
        justify-content: center;
        flex-direction: column;
        gap: 2rem;
        align-items: center;
        width: 100vw;
        height: 100%;
    }

    .aufbau h1{
        color: white;
        font-size: 4rem;
    }

    .aufbau h2{
        padding: 0rem 0.5rem 5rem 0.5rem;
        text-align: center;
        font-weight: 400;
        color: white;
        font-size: 2rem;
    }

    .mail{
        border-bottom: 1pt solid;
        color: white;
        opacity: 0.9;
        font-weight: 300;
    }

    .mail:hover{
        opacity: 1;
    }

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

    nav a:hover {
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
