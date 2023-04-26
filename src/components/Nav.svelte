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
        font-size: 3rem !important;
    }
    a{
        font-weight: 500;
        font-size: 1.6rem;
        text-decoration: none;
        color: rgb(0, 0, 0);
        transition: all 0.2s ;

    }

    a:hover{
        color: #ff4500;
    }

    .kontakt{
        border-radius: 0.5rem;
        color: white;
        padding: 1rem;
        transition: all 0.5s ease;
        font-weight: 500;
        background-color: orangered;
    }

    .kontakt:hover{
        color: white;
        background-color: black;
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