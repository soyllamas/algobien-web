<script:head>
    <title>Puerto Escondido, México — 10/10</title>
</script:head>

<script>
    import Introduction from "$lib/Introduction.svelte";

    const places = $state([
        {
            name: "Café Olé",
            category: "breakfast",
            description: "Desayuno de surfista.",
            recommendations: [
                "Waffles con tocino",
                "Crepas con crema",
            ]
        }
    ]);
</script>

<Introduction
        title="📍 Querétaro, México"
        description="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."/>
<div class="mt-12">
    <h3 class="text-xl font-medium mb-6">🍳️Desayuno</h3>
    {#each places as place}
        <a href="https://maps.google.com"
           class="border border-slate-300 p-4 block rounded-xl my-3 hover:bg-slate-50"
           target="_blank">
            <p class="font-medium">{place.name}</p>
            <p class="text-sm my-1">{place.description}</p>
            <div class="inline-block">
                {#each place.recommendations as recommendation}
                    <p class="inline-block text-[12px] bg-slate-100 rounded-full px-2 py-[2px] mr-1">{recommendation}</p>
                {/each}
            </div>
        </a>
    {/each}
</div>
<div class="mt-12">
    <h3 class="text-xl font-medium mb-6">🍽️ Comida</h3>
</div>
<div class="mt-12">
    <h3 class="text-xl font-medium mb-6">🍝️️ Cena</h3>
</div>
<div class="mt-12">
    <h3 class="text-xl font-medium mb-6">🥂️ Bares & Antros</h3>
</div>