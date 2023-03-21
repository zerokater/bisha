<script>
    import { trusted } from "svelte/internal";


    let title = "bisha. | Kreative Branding-Agentur | Markenbildung & Design-Lösungen in Ihrer Region"

    window.onblur = function(){
        title = "Hallo??!";
    }

    window.onfocus = function(){
        title = "bisha. | Kreative Branding-Agentur | Markenbildung & Design-Lösungen in Ihrer Region";
    }
</script>

<head>
	<title>{title}</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kreative Branding-Agentur, die Unternehmen durch erstklassiges Branding, innovatives Design und individuelle Strategien zum Erfolg verhilft. Erfahren Sie mehr und kontaktieren Sie uns jetzt!">
	<meta name="keywords" content="bisha, Branding-Agentur, Markenbildung, Design, Wallis, Markenstrategie, Logo-Design, Verpackungsdesign, Marketingmaterialien, Unternehmenserfolg" />
	<html lang="en" />
</head>

<div class="aufbau">
    <h1>bisha.</h1>
    <h2>Die Website befindet sich derzeit im Aufbau.</h2>
    <a class="mail" href="mailto:info@bisha.ch">info@bisha.ch</a>
</div>

<p>mergim scemo</p>
<!-- <h1>Von der Entwicklung neuer Marken bis hin zum kleinsten Detail im Design.</h1>
<h2>Kreativagentur, die Unternehmen hilft, sich als Branchenführer zu profilieren.</h2> -->


<style>


.aufbau{
        position: absolute;
        top: 0;
        left: 0;
        background-color: orangered;
        display: flex;
        justify-content: center;
        flex-direction: column;
        gap: 2rem;
        align-items: center;
        width: 100vw;
        height: 100%;
    }

    .aufbau h1{
        color: white;
        font-size: 4rem;
    }

    .aufbau h2{
        padding: 0rem 0.5rem 5rem 0.5rem;
        text-align: center;
        font-weight: 400;
        color: white;
        font-size: 2rem;
    }

    .mail{
        border-bottom: 1pt solid;
        color: white;
		font-size: 2rem;
        opacity: 0.9;
        font-weight: 300;
    }

    .mail:hover{
        opacity: 1;
    }

</style>