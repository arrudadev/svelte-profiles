<script lang="ts">
  import Title from "./components/Title.svelte";
</script>

<div class="app">
  <header>
    <Title />
  </header>
</div>

<style>
  .app {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
</style>
