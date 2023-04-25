<script>
	import Projekt from '/src/components/Projekt.svelte';
    import ProjekteJSON from '/src/routes/projekte/Projekte.json';
</script>

<head>
	<title>bisha. | Kreative Branding-Agentur | Markenbildung & Design-Lösungen in Ihrer Region</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kreative Branding-Agentur, die Unternehmen durch erstklassiges Branding, innovatives Design und individuelle Strategien zum Erfolg verhilft. Erfahren Sie mehr und kontaktieren Sie uns jetzt!">
	<meta name="keywords" content="bisha, Branding-Agentur, Markenbildung, Design, Bisha Wallis, Markenstrategie, Logo-Design, Verpackungsdesign, Marketingmaterialien, Unternehmenserfolg" />
	<html lang="en" />
</head>

<main>
	<section class="headline">
		<h1>Ihre Marke gut gestaltet.</h1>
		<h2>Ihr <span>Erfolg</span> durch individuelles <span>Design</span>.</h2>
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
.headline {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  height: auto;
}

span {
  color: orangered;
}

main {
  display: flex;
  flex-direction: column;
  gap: 3rem;
}

.dienstleistungen {
  display: flex;
  gap: 2rem;
}

.leistungen-box {
  width: 300px;
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
  padding: 1.5rem;
  border-radius: 0.5rem;
}

@media only screen and (max-width: 700px) {
  .dienstleistungen {
    flex-wrap: wrap;
    width: auto;
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