<script>
	import Projekt from '/src/components/Projekt.svelte';
  import ProjekteJSON from '/src/routes/projekte/Projekte.json';
</script>

<head>
	<title>bisha. | Kreative Branding-Agentur | Markenbildung & Design-Lösungen in Ihrer Region</title>
    <meta name="description" content="Kreative Branding-Agentur, die Unternehmen durch erstklassiges Branding, innovatives Design und individuelle Strategien zum Erfolg verhilft. Erfahren Sie mehr und kontaktieren Sie uns jetzt!">
	  <meta name="keywords" content="bisha, Branding-Agentur, Markenbildung, Design, Bisha Wallis, Markenstrategie, Logo-Design, Verpackungsdesign, Marketingmaterialien, Unternehmenserfolg" />
    <link rel="canonical" href="https://bisha.ch/">
</head>

<main>
	<section class="headline">
		<h1>Ihre Marke gut gestaltet.</h1>
		<h2>Ihr <span>Erfolg</span> durch individuelles <span>Design</span>.</h2>
	</section>
  <section class="projekte" >
    <img class="projekt-image" src="images/tafa.jpg" alt="">
    <img class="projekt-image" src="images/tafa.jpg" alt="">
    <img class="projekt-image" src="images/tafa.jpg" alt="">
    <img class="projekt-image" src="images/tafa.jpg" alt="">
    <img class="projekt-image" src="images/tafa.jpg" alt="">
    <img class="projekt-image" src="images/tafa.jpg" alt="">
  </section>

</main>



<style>	
main {
  display: flex;
  flex-direction: column;
  gap: 3rem;
}
.headline {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}


.projekte{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  row-gap: 4rem;
}
.projekt-image{
  border: 1pt solid rgb(157, 157, 157);
  width: 30%;
  box-shadow: rgba(101, 107, 112, 0.2) 0px 8px 24px;
  border-radius: 0.5rem;

}

@media only screen and (max-width: 768px) {
  
  .projekte{
    row-gap: 2.5rem;
  }
  
  .projekt-image {
    width: 47.5%;
  }
}
@media only screen and (max-width: 480px) {
  
  .projekte{
    row-gap: 2rem;
  }
  
  .projekt-image {
    width:  100%;
  }
}
</style>

<!--https://schum123.github.io/svelte-loading-spinners/?ref=madewithsvelte.com-->