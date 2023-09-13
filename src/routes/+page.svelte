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

	<section class="uber-uns" >

	</section>



</main>



<style>	

	main{
		display: flex;
		flex-direction: column;
		gap: 5rem;
	}

	.headline{
		display: flex;
		flex-direction: column;
		gap: 1rem;
		height: auto;
	}


	.uber-uns{
		height: 40rem;
		background-color: orangered;
	}

	span{
		color: orangered;
	}



</style>

<!--https://schum123.github.io/svelte-loading-spinners/?ref=madewithsvelte.com-->