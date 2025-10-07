<script lang="ts">
    let fkingerror = " >> Spookymonth by SrPelo << ";
    let d = new Date();
</script>

<main>
    <h3>
        Welcome at isitspookymonthdotcom | made by <a
            href="https://hactuss-website.vercel.app">hactuss</a
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
    {:else}
        <p>no</p>
    {/if}
    {#if d.getMonth() == 9}
        <div>
            <h1>Happy Spooky Month</h1>
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
    {/if}
</main>
