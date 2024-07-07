<script>
    import "../app.css";
    import Navigation from "$lib/Navigation.svelte";
</script>

<Navigation/>
<div class="h-16"></div>
<div class="px-8 md:mx-auto max-w-xl py-12">
    <slot/>
</div>

<style lang="postcss">
    :global(*) {
        font-family: 'IBM Plex Sans', sans-serif;
    }
</style>
