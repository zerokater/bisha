<script>
  import { dev } from '$app/environment';
  import { inject } from '@vercel/analytics';


  inject({ mode: dev ? 'development' : 'production' });
</script>
<!-- +layout.svelte -->
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