<header>
    <a href="/"><h1>bisha.</h1></a>
    <nav>
        <a href="/projekte">projekte</a> 
        <a class ="kontakt" href="/kontakt">kontakt</a>
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
        border-radius: 0.5rem;
        box-shadow: orangered 0px 0px 0px 2.5px;
        color: orangered;
        padding: 0.7rem;
        transition: all 0.3s;
        font-weight: 500;
    }

    .kontakt:hover{
        background-color: orangered;
        box-shadow: none;
        color: white;
       }

    @media only screen and (max-width: 600px) {
        header{
            height: 7rem;
        }

    }


</style>