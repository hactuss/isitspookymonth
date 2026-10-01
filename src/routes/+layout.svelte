<script lang="ts">
    import favicon from "$lib/assets/spooky.png";
    import { MetaTags } from "svelte-meta-tags";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    {#if new Date().getMonth() == 9}
        <MetaTags
            title="IT IS DA SPOOKY MONTH!!!"
            description=""
            canonical="https://isitspookymonth.vercel.app"
            openGraph={{
                type: "website",
                url: "https://isitspookymonth.vercel.app",
                images: [
                    {
                        url: "https://tenor.com/de/view/spooky-month-spooky-dance-gif-2212774558457813484",
                        alt: "spookykids",
                        width: 254,
                        height: 240,
                        type: "image/gif",
                    },
                ],
            }}
        />
    {:else}
        <title>Is it spooky month?</title>
    {/if}
    <link rel="apple-touch-icon" href={favicon} type="image/png" />
</svelte:head>

{@render children?.()}
