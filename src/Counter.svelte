<script>
    let count = 0;

    setInterval(function () {
        count += 1;
    }, 1000);
</script>

<svelte:options tag="counter-app"></svelte:options>

<main>
    <h1>Count: {count}</h1>
</main>