<script>
    import ProjektJSON from '/src/routes/projekte/Projekte.json';
    export let projekt = "alo";
</script>


<div title={projekt.img_alt} class="projekt-box" style="background-image: url({projekt.img});"></div>






<style>
    .projekt-box{
        cursor: pointer;
        background-position: center;
        background-repeat: no-repeat;
        background-size: contain;
        padding: 1rem;
        box-shadow: rgba(101, 107, 112, 0.2) 0px 8px 24px;
        background-color: white;
        border-radius: 0.5rem;
        flex-grow: 1;
        /*flex-grow: 1;
        flex-shrink: 1;*/
        width: 15rem;
        height: 15rem;
    }
</style>