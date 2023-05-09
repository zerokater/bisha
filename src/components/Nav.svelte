<header>
    <nav>
        <a class="logo" href="/"><h1>bisha.</h1></a>
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


    a{
        text-decoration: none;
    }
    h1{
        color: black;
        font-size: 3em !important;
    }

    .nav-links{
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .nav-link{
        text-decoration: none !important;
        color: black;
        font-size: 2rem;
    }

    .kontakt{   
        border-radius: 0.5rem;
    }

    @media screen and (max-width: 1200px) {

        
        nav{
        padding: 0rem 2rem 0rem 2rem;
        }
    }

</style>