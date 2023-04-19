<script>
    import Nav from '/src/components/Nav.svelte';
</script>

<Nav/>

<slot />

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
