<script>
    import Nav from '/src/components/Nav.svelte';
    import Footer from '/src/components/Footer.svelte';


    import { dev } from '$app/environment';
    import { inject } from '@vercel/analytics';
 
    inject({ mode: dev ? 'development' : 'production' });
</script>

<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>


<slot />



<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
  :global(*) {
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

  :global(html){
    font-size: 10px;
  }
  :global(section){
    margin: auto;
    width: 1120px;
  }

  :global(h2){
    color: orangered;
  }

  :global(span){
    background-color: orangered;
  }

  :global(h1){
    color: black;
    line-height: 120%;
    font-size: 7rem;
  }

  :global(h2){
        text-decoration: underline;
        text-decoration-color: orangered;
        color: black;
        font-size: 3.5rem;
        font-weight: 400;
  }

  :global(h3){
        font-size: 3rem;
        text-decoration: underline;
        text-decoration-color: orangered;
    }


    :global(p){
        font-size: 2.5rem;
    }

    @media screen and (max-width: 1200px) {
  

      :global(section){
        padding: 2rem 2rem 2rem 2rem;
      }

      :global(h1){
        font-size: 6rem;
      }

      :global(h2){
        font-size: 3rem;
      }

    }

    @media screen and (max-width: 768px) {
      :global(h1){
        font-size: 5rem;
      }

      :global(h2){
        font-size: 2.5rem;
      }

      :global(p){
        font-size: 1.8rem;
      }

      :global(h3){
        font-size: 2.5rem;
      }

    }

    @media screen and (max-width: 650px) {

      :global(h1){
        font-size: 3.5rem;
      }

      :global(h2){
        font-size: 2rem;
      }

      :global(h3){
        font-size: 2.3rem;
      }

      :global(p){
        font-size: 1.7rem;
      }

    }

    @media screen and (max-width: 480px) {
        :global(h1){
          font-size: 2.8rem;
        }
  
        :global(h2){
          font-size: 1.9rem;
        }

        :global(h3){
          font-size: 1.8rem;
        }

        :global(p){
          font-size: 1.6rem;
        }
        

      }
  
  
</style>