<script lang="ts">
  import 'papercss/dist/paper.min.css'
  import Navbar from './components/Navbar.svelte'
  import FirstEntry from './entries/FirstEntry.svelte'
</script>

<main>
  <Navbar />
  <FirstEntry />
</main>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
  }

  :global(*) {
    background-color: lightgrey;
  }
</style>
