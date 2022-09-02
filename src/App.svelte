<script lang="ts">
  import Titulo from "./components/Titulo.svelte";
</script>

<div class="app">
  <header>
    <Titulo />
  </header>
</div>

<style>
  .app {
    max-height: 100vh;
  }
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
</style>
