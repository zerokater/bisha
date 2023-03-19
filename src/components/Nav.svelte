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
        gap: 2rem;
        align-items: center;
    }


    a{
        font-weight: 500;
        font-size: 1.6rem;
        text-decoration: none;
        color: black;
        transition: 0.3s color ;

    }

    a:hover{
        color: orangered;
    }

    .kontakt{
        background-color: orangered;
        border-radius: 0.5rem;
        color: white;
        padding: 0.5rem;
        border: 2pt solid orangered;
        transition: 0.3s background-color;
        font-weight: 500;
    }

    .kontakt:hover{
        background-color: white;
        color: orangered;
    }

    @media only screen and (max-width: 600px) {
        header{
            height: 7rem;
        }

    }


</style>