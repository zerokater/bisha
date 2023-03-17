<script>
    import Nav from '/src/components/Nav.svelte';
</script>

<Nav/>
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
      width: 70%;
      margin: 0 auto;
    }

    :global(p){
      font-size: 62.5%;
    }
  </style>
<slot />
