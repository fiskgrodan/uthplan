<script>
  import { page } from "$app/stores";

  $: classname =
    $page.params.class[0].toUpperCase() + $page.params.class.slice(1);
</script>

<svelte:head>
  <title>Uthplan {classname}</title>
</svelte:head>

<main>
  <div class="classname">{classname}</div>
</main>

<style>
  main {
    width: 1000px;
    margin: auto;
    padding-top: 20px;
  }

  .classname {
    text-transform: capitalize;
  }
</style>
