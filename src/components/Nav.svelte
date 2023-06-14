<header>
    <nav>
        <a href="/"><img id="logo" src="images/bisha-logo-svg-schwarz.svg" alt="logo bisha"></a>
        <div class="nav-links">
            <a class="nav-link" href="/dienstleistungen">dienstleistungen</a> 
            <a class="nav-link kontakt" href="/kontakt">kontakt</a>
        </div>
    </nav>
</header>

<style>
    header{
        
        min-height: 10rem;
        background-color: white;
        justify-content: center;
        align-items: center;
        display: flex;
    }
    
    nav{
        width: 1120px;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 2rem;

        
    }


    #logo{
        width: 80px;
    }

    a{
        text-decoration: none;
    }

    .nav-links{
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .nav-link{
        text-decoration: none !important;
        color: black;
        font-size: 1.6rem;
    }

    .kontakt{   
        border-radius: 0.5rem;
    }

    @media screen and (max-width: 1200px) {

        
        nav{
        padding: 0rem 2rem 0rem 2rem;
        }
    }
    

    @media screen and (max-width: 480px) {

        header{
            min-height: 7rem;
        }

        .nav-link{
            font-size: 1.6rem;
        }

    }

</style>