<script lang="ts">
    import "../app.css";
    import favicon from "$lib/assets/spooky.png";

    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <title>Is it spooky month?</title>
</svelte:head>

{@render children?.()}
