<header>
    <a href="/"><h1>bisha.</h1></a>
    <nav>
        <a href="/projekte">Projekte</a>
        <a class ="kontakt" href="/kontakt">Kontakt</a>
    </nav>
</header>

<style>
    header{
        width: 100%;
        height: 10rem;
        display: flex;
        align-items: center;
        justify-content: space-between;

    }

    nav{
        display: flex;
        gap: 1rem;
        align-items: center;
    }


    a{
        font-size: 1.6rem;
        text-decoration: none;
        color: black;
        transition: 0.3s color ;
    }

    a:hover{
        color: orangered;
    }

    .kontakt{
        border-radius: 0.2rem;
        color: orangered;
        padding: 0.4rem;
        border: 2pt solid orangered;
        background-color: white;
        transition: 0.3s background-color;
        font-weight: 400;
    }

    .kontakt:hover{
        background-color: orangered;
        color: white;
    }


</style>