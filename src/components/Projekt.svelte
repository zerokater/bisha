<script>
    import ProjektJSON from '/src/routes/projekte/Projekte.json';
    export let projekt = "alo";
</script>

<div class="projekt-box" style="background-image: url({projekt.img});">
    <h1>{projekt.name}</h1>
    <h3>{projekt.typ}</h3>
</div>


<style>
    .projekt-box{
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        padding: 1rem;
        box-shadow: rgba(101, 107, 112, 0.2) 0px 8px 24px;
        background-color: white;
        border-radius: 0.5rem;
        width: 20rem;
        height: 20rem;
    }
</style>