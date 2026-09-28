<script>
    import {onMount} from 'svelte'
    let Carousel = $state();

    onMount(async () => {
        const module = await import("svelte-carousel");
        Carousel = module.default;
    });

    let imagenes = [
        { image: "https://picsum.photos/id/1015/800/500" },
        { image: "https://picsum.photos/id/1016/800/500" },
        { image: "https://picsum.photos/id/1018/800/500" },

    ] 
</script>

{#if Carousel}
    <Carousel autoplay autoplayDuration={2000}>
        {#each imagenes as item}
            <img src={item.image} alt="imagen" />
        {/each}
    </Carousel>
{/if}

<style>
    img {
        width: 100%;
    }
</style>
