<header>
    <a href="/"><h1>bisha.</h1></a>
    <nav>
        <a href="/projekte">projekte</a> 
        <a class ="kontakt" href="/kontakt">kontakt</a>
    </nav>
</header>

<style>

    header{
        margin-top: 2rem;
        width: 100%;
        height: auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 5rem;

    }

    nav{
        display: flex;
        gap: 2rem;
        align-items: center;
    }


    h1{
        color: black !important;
        font-size: 3rem !important;
    }
    a{
        font-weight: 500;
        font-size: 1.6rem;
        text-decoration: none;
        transition: all 0.2s ease;
        color: black;
    }

    a:hover{
        color: orangered;
    }







    @media only screen and (max-width: 768px) {

        header{
            margin-bottom: 3rem;
        }


    }

    @media only screen and (max-width: 768px) {

        header{
            margin-bottom: 0rem;
        }


    }


</style>