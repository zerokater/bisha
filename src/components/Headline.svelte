<script>
    import { onMount, onDestroy } from 'svelte';
import { slide, fade } from 'svelte/transition';

let greetings = ['Logo', 'Visitenkarte', 'Flyer','Foto', 'Pizza', 'Broschüre', 'Video', 'Animation', 'Visitenkarte'];
let index = 0;
let roller;

onMount(() => {
    roller = setInterval(() => {
        if (index === greetings.length - 1) index = 0;
        else index++;
    }, 1250);
});

onDestroy(() => {
    clearInterval(roller);
});
</script>




<h1>Wir Machen</h1>
{#key index}
    <h1> <span> {greetings[index]}.</span></h1>
{/key}



<style>
    h1{
        line-height: 90%;
    }
    span{
        color: orangered;
    }
</style>