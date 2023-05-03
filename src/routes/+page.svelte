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
		<h2>Ihr Erfolg durch individuelles Design.</h2>
	</section>
  <section class="uber-uns" >
    <p>Bisha ist eine kreative Branding-Agentur, die sich auf die Entwicklung einzigartiger visueller Identitäten spezialisiert hat. Wir sind der Meinung, dass gutes Design mehr ist als nur Ästhetik - es sollte eine Geschichte erzählen und eine Verbindung zwischen Ihrer Marke und Ihren Kunden schaffen.</p>
    <a href="/kontakt">Kontaktiere Uns</a>
  </section>
  <section class="projekte">
    <img src="images/tafa.jpg" alt="">
    <img src="images/tafa.jpg" alt="">
    <img src="images/tafa.jpg" alt="">
    <img src="images/tafa.jpg" alt="">
    
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
  gap: 1rem;
}

.uber-uns{
  display: flex;
  flex-direction: column;
  gap: 1rem;
  width: 700px;
}

.uber-uns a{
  border-radius: 0.5rem;
  color: white;
  padding: 1rem;
  transition: all 0.5s ease;
  font-weight: 500;
  background-color: orangered;
  font-weight: 500;
  font-size: 1.6rem;
  text-decoration: none;
  width: 150px;
}

.uber-uns a:hover{
  scale: 0.95;
  color: white;

}

.projekte{
  display: flex;
  width: 100%;
  flex-wrap: wrap;
  row-gap: 3rem;
  justify-content: space-between;
}

.projekte img{
  width: 30%;
  border: 1pt solid rgb(233, 233, 233);
  box-shadow: rgba(0, 0, 0, 0.05) 0px 6px 24px 0px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px;
  border-radius: 0.5rem;
  
}
  

@media only screen and (max-width: 1120px) {
  .uber-uns {
    width: 75%;
  }
}

@media only screen and (max-width: 768px) {

  .projekte{
    row-gap: 2rem;
  }
  .projekte img{
    width: 47.5%;
  }
  
  .uber-uns{
    width: auto;
  }

}

</style>

<!--https://schum123.github.io/svelte-loading-spinners/?ref=madewithsvelte.com-->