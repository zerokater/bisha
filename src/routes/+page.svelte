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

  <section class="einleitung">

  </section>

	<section class="dienstleistungen" >
		<div class="leistungen-box">
			<h2>Foto</h2>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero natus at ad. Nihil eum minus asperiores omnis esse amet voluptatem nisi quod! Accusamus sequi dolores omnis temporibus fuga, delectus aut?</p>
		</div>
		<div class="leistungen-box">
			<h2>Video</h2>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque molestias dolorem ut sit sed quia voluptates provident. Unde labore quod qui! Qui quibusdam earum hic. Magnam itaque iure nobis reiciendis.</p>
		</div>
		<div class="leistungen-box">
			<h2>Brand</h2>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore ex illum consectetur at iusto culpa nesciunt nisi atque nobis ducimus explicabo similique necessitatibus illo vitae ut, delectus vel assumenda placeat?</p>
		</div>
	</section>



</main>



<style>	
main {
  display: flex;
  flex-direction: column;
  gap: 3rem;
}
.headline {
  text-align: center;
  display: flex;
  flex-direction: column;
  gap: 1rem;
  height: auto;
}

span {
  color: orangered;
}

.einleitung{
  height: 40rem;
  border-radius: 0.5rem;
  background-image: url("images/media.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

.dienstleistungen {
  display: flex;
  gap: 2rem;
  justify-content: space-between;
}

.leistungen-box {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 320px;
  height: 320px;
  color: rgb(70, 70, 70);
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
  padding: 2.5rem;
  border-radius: 0.5rem;
}


@media only screen and (max-width: 700px) {
  .dienstleistungen {
    flex-wrap: wrap;

  }

  .leistungen-box {
    width: auto;
    height: auto;
  }
}

@media only screen and (max-width: 586px) {
  .leistungen-box {
    width: auto;
    height: auto;
  }
}
</style>

<!--https://schum123.github.io/svelte-loading-spinners/?ref=madewithsvelte.com-->