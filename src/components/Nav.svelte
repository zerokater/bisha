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
        background: rgb(0, 0, 0);
        background: linear-gradient(31deg, rgba(255,69,0,1) 0%, rgba(255,169,0,1) 100%);
        border-radius: 0.5rem;
        color: white;
        padding: 0.7rem;
        transition: 0.3s transform ;
        font-weight: 500;
    }

    .kontakt:hover{
        transform: scale(1.04);
        color: white;
       }

    @media only screen and (max-width: 600px) {
        header{
            height: 7rem;
        }

    }


</style>