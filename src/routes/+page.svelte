<svelte:head>
    <title>10/10 — Comidas & Bebidas</title>
</svelte:head>
<nav class="border-b-2 border-b-gray-200 fixed w-full bg-white h-16 grid place-items-center z-50">
    <h1 class="text-center bg-black font-medium text-white px-2">10/10</h1>
</nav>
<div class="h-16"></div>
<div class="md:mx-auto max-w-3xl px-4 py-12">
    <h2 class="text-2xl font-medium md:text-4xl">Una colección de recomendaciones que quieres tener en el radar.</h2>
    <p class="md:text-lg text-gray-400 mt-4">Explora una cuidada selección de restaurantes, bares, cafeterías y
        otros conceptos de los que vas a necesitar saber más.</p>
</div>
<div class="grid md:grid-cols-3 gap-4 mx-auto max-w-5xl px-4 pb-4">
    <div class="destination bg-[url('https://firebasestorage.googleapis.com/v0/b/soy-llamas.appspot.com/o/destinations%2Fpuerto-escondido%2FPE_5.jpg?alt=media&token=9a4515cf-ca3d-4ddf-b623-a76f7a586466')]">
        <p class="destination-title">Puerto Escondido</p>
    </div>
    <div class="destination bg-[url('/los-cabos.jpg')]">
        <p class="destination-title">Los Cabos</p>
    </div>
    <div class="destination bg-[url('/qro.jpg')]">
        <p class="destination-title">Querétaro</p>
    </div>
    <div class="destination bg-[url('/valle.jpg')]">
        <p class="destination-title">Valle de Bravo</p>
    </div>
</div>

<style lang="postcss">
    h1 {
        font-family: 'IBM Plex Mono', monospace;
    }

    h2, p {
        font-family: 'IBM Plex Sans', sans-serif;
    }

    .destination {
        @apply rounded-xl h-[80vh] bg-cover relative bg-center
    }

    .destination-title {
        @apply absolute bottom-0 left-0 rounded-xl text-white font-semibold px-6 py-8 text-5xl bg-gradient-to-t from-[#00000080] to-[#00000000] w-full
    }
</style>