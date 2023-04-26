<script>
    import Projekt from '/src/components/Projekt.svelte';
    import ProjekteJSON from '/src/routes/projekte/Projekte.json';
</script>

<head>
    <link rel="canonical" href="https://bisha.ch/projekte">
</head>

<h1>Unsere Projekte</h1>
<!--<h1>Unsere ausgewählten Projekte</h1>

<main>
    <section>
        <Projekt projekt={ProjekteJSON.taffa}/>
        <Projekt projekt={ProjekteJSON.taffa}/>
        <Projekt projekt={ProjekteJSON.taffa}/>
        <Projekt projekt={ProjekteJSON.taffa}/>
        <Projekt projekt={ProjekteJSON.taffa}/>
    </section>
</main>
-->


<style>
    main{
        width: 100%;
        height: auto;
    }
    section{
        justify-content: start;
        display: flex;
        gap: 2rem;
        flex-flow: wrap;
        width: 100%;
        height: auto;
    }
</style>

