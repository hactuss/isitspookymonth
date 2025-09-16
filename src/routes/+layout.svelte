<script lang="ts">
    import "../app.css";
    import favicon from "$lib/assets/spooky.png";

    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <title>Is it spooky month?</title>
    <link rel="apple-touch-icon" href={favicon} type="image/png" />
</svelte:head>

{@render children?.()}
