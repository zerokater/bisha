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

  :global(body){
    width: 1000px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }


  :global(p){
    font-size: 1.6rem;
  }

  :global(h1){
    color: orangered;
    line-height: 100%;
    font-size:6.5rem;
    font-weight: 700;
  }

  :global(h2){
    font-weight: 300;
    line-height: 100%;
    font-size:3.5rem;
    color: black;
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
    font-size: 2.5rem;
  }

}


}
</style>
