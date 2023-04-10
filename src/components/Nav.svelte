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
        height: 8rem;
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
        color: rgb(0, 0, 0);
        transition: all 0.2s ;

    }

    a:hover{
        color: orangered;
    }

    .kontakt{
        border-radius: 0.5rem;
        box-shadow: orangered 0px 0px 0px 2.5px;
        -webkit-box-shadow: orangered 0px 0px 0px 2.5px;
        -moz-box-shadow: orangered 0px 0px 0px 2.5px;
        color: orangered;
        padding: 0.7rem;
        transition: all 0.5s;
        font-weight: 500;
    }

    .kontakt:hover{
        scale: 0.95;
        background-color: orangered;
        box-shadow: none;
        color: white;
       }

</style>