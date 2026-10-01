<script lang="ts">
    import favicon from "$lib/assets/spooky.png";
    import { MetaTags } from "svelte-meta-tags";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    {#if new Date().getMonth() == 9}
        <meta title="IT IS DA SPOOKY MONTH!!!" />
        <meta
            property="og:image"
            content="https://c.tenor.com/HrVavLTmWewAAAAd/tenor.gif"
        />
        <meta property="og:image:type" content="image/gif" />
        <meta property="og:image:width" content="254" />
        <meta property="og:image:height" content="240" />

        <meta
            property="twitter:image:src"
            content="https://c.tenor.com/HrVavLTmWewAAAAd/tenor.gif"
        />
        <meta name="twitter:card" content="summary_large_image" />
    {:else}
        <title>Is it spooky month?</title>
    {/if}
    <link rel="apple-touch-icon" href={favicon} type="image/png" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

{@render children?.()}
