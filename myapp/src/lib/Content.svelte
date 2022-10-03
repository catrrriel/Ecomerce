<script>
  import Shop from "./Shop.svelte";

  let shop = true;

  let arr = ["ola", "ola2", "ola3"];
</script>

<main>
  {#if shop}
    <Shop />
  {:else}
    <p>pagos</p>
  {/if}

  {#each arr as e}
    <p>{e}</p>
  {/each}
</main>

<style>
  main {
    /* margin-top: 75px; */
    width: 100%;
    height: auto;
    background-color: blue;
  }
</style>
