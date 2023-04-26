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

<Nav/>

<slot />

<Footer/>


<style>
  :global(*) {
    font-family: 'Ubuntu', sans-serif;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

  :global(html){
    font-size: 10px;
  }

  :global(body){
    width: 1000px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
    background-color:#f3f4f6;
  }


  :global(p){
    font-size: 2rem;
  }

  :global(h1){
    
    line-height: 100%;
    font-size:6.5rem;
  }

  :global(h2){
    font-weight: 400;
    font-size:3.5rem;
  }


  @media only screen and (max-width: 1120px) {
  :global(body) {
    width: 90%;
  }

  @media only screen and (max-width: 768px) {

  :global(h1){
    font-size: 4.5rem;
  }
  :global(h2){
    font-size: 2.5rem;
  }


}


@media only screen and (max-width: 480px) {
  :global(h1){
    font-size: 4.5rem;
  }
  :global(h2){
    font-size: 2rem;
  }

}


}
</style>
