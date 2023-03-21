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
    background-color: dimgray;
    width: 1000px;
    margin: 0 auto;
  }

  :global(p){
    font-size: 2rem;
  }


  @media only screen and (max-width: 1120px) {
  :global(body) {
    width: 90%;
  }

}
</style>
