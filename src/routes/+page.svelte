<script lang="ts">
    let yesorno = "no";
    let display = "none";
    let date = new Date();
    console.log("test");
    const month = date.getMonth();
    console.log(month);
    if (month == 9) {
        yesorno = "Yes";
        display = "block";
    } else {
    }
</script>

<main class="">
    <h3>Welcome at isitspookymonthdotcom</h3>
    <h1>Is it spookymonth?</h1>
    <h2>{yesorno}</h2>
    <div style="display: {display};" id="spookykids">
        <h1 style="display: {display};">Happy Spooky Month</h1>
        <img
            src="https://media.tenor.com/agWRnwIHk0MAAAAj/%D0%B6%D1%83%D1%82%D0%BA%D0%B8%D0%B9%D0%BC%D0%B5%D1%81%D1%8F%D1%86-%D1%81%D0%BA%D0%B8%D0%B4%D0%B8%D0%BF%D0%B0%D0%BC%D0%BF.gif"
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
</main>
