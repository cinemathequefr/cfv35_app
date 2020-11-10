<script>
  import Menu from "../components/Menu.svelte";
  export let segment;
</script>

<style>
</style>

<Menu {segment} />
<main>
  <slot />
</main>
