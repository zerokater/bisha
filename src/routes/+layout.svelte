<!-- +layout.svelte -->
<style>
    :global(*) {
      font-family: 'Ubuntu', sans-serif;
      box-sizing: border-box;
      padding: 0;
      margin: 0;
    }

    :global(body){
      width: 70%;
      margin: 0 auto;
    }
  </style>
  
  <header>
    <!-- your header content here... -->
  </header>
  
  <main>
    <slot />
  </main>
  
  <footer>
    <!-- your footer content here... -->
  </footer>