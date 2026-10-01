<script lang="ts">
    import { SvelteDate } from "svelte/reactivity";

    let fkingerror = " >> Spookymonth by SrPelo << ";
    let d = new SvelteDate();
</script>

<main>
    <h3>
        Welcome at isitspookymonthdotcom | made by <a
            href="https://haj-links.vercel.app">hactuss</a
        >
        | for my friend | watch
        <a
            href="https://www.youtube.com/playlist?list=PLlgnRq26EmwJ-sDDKtiaVj-fuIGwrzCYG"
        >
            {fkingerror}
        </a> here
    </h3>
    <h1>Is it spookymonth?</h1>

    {#if d.getMonth() == 9}
        <p>yes</p>
        <div>
            <h1>Happy Spooky Month</h1>
            <div>
                <img
                    src="https://media.tenor.com/agWRnwIHk0MAAAAj/%D0%B6%D1%83%D1%82%D0%BA%D0%B8%D0%B9%D0%BC%D0%B5%D1%81%D1%8F%D1%86-%D1%81%D0%BA%D0%B8%D0%B4%D0%B8%D0%BF%D0%B0%D0%BC%D0%BF.gif"
                    alt=""
                />
                <img
                    src="https://media1.tenor.com/m/HrVavLTmWewAAAAd/spooky-month-spooky-dance.gif"
                    alt=""
                />
                <img
                    src="https://media1.tenor.com/m/MUKNVPLzWsQAAAAd/itisaspookymonth.gif"
                    alt=""
                />
            </div>
            <iframe
                width="560"
                height="315"
                src="https://www.youtube.com/embed/xuJM6Y-ljbo?si=0jrf75z8BS8lalw_"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin"
                allowfullscreen
            ></iframe>
        </div>
    {:else}
        <p>no</p>
    {/if}
</main>

<style>
    @import "tailwindcss";
    @import url("https://fonts.googleapis.com/css2?family=Archivo+Black&family=Goldman:wght@400;700&family=Reddit+Mono:wght@200..900&family=Reddit+Sans:ital,wght@0,200..900;1,200..900&family=Ultra&display=swap");
    @font-face {
        font-family: "Ultra";
        src: url("./../lib/assets/Ultra/Ultra-Regular.ttf") format("opentype");
    }

    .ultra-regular {
        font-family: "Ultra", serif;
        font-weight: 400;
        font-style: normal;
    }
    .archivo-black-regular {
        font-family: "Archivo Black", sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    :global {
        :root {
            font-size: 1rem;
            color: orange;
        }
        * {
            margin: 0;
        }
        html {
            background-color: black;
        }
    }
    main {
        background-color: black;
        width: 100%;
        height: 100%;
    }
    h1 {
        font-size: 3rem;
        font-family: "Ultra";
    }

    h3 {
        border: 1px solid orange;
    }
    img {
        width: 300px;
    }
    a {
        text-decoration: underline;
    }
</style>
