<script lang="ts">

    let count = 0;
    const increment = () => {
        count++;
    }

</script>

<button on:click={increment} class="button">
    Counter: {count}
</button>

<style>
    button {
        background-color: rgb(70, 70, 70);
        padding: 8px;
        border: none;
        border-radius: 4px;
        color: #fff;
        font-size: 1rem;
    }
</style>