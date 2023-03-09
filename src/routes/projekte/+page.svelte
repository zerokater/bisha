<script>
    import Nav from '/src/components/Nav.svelte';
    import Projekt from '/src/components/Projekt.svelte';
    import ProjekteJSON from '/src/routes/projekte/Projekte.json';
</script>

<Nav/>
<main>
    <section>
        <Projekt projekt={ProjekteJSON.taffa}/>
        <Projekt projekt={ProjekteJSON.test}/>
        <Projekt/>
        <Projekt/>
        <Projekt/>
    </section>
</main>



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
