<svelte:head>
    <title>Restaurantes, cafeterías, bares y más — 10/10</title>
</svelte:head>

<script>
    import Introduction from "$lib/Introduction.svelte";
</script>

<Introduction
        title="👋🏼 Sobre nosotros"
        description="Somos una curada colección de restaurantes, cafeterías, bares y lugares de interés que
            quieres tener en el radar."/>
<div class="mt-12">
    <h3 class="text-xl font-medium mb-6">🏝️ Destinos</h3>
    <a href="/puerto-escondido" class="border border-slate-300 p-4 block rounded-xl my-3 hover:bg-slate-50">
        Puerto Escondido, México
    </a>
    <a href="/los-cabos" class="border border-slate-300 p-4 block rounded-xl my-3 hover:bg-slate-50">
        Los Cabos, México
    </a>
    <a href="/queretaro" class="border border-slate-300 p-4 block rounded-xl my-3 hover:bg-slate-50">
        Queretaro, México
    </a>
</div>
