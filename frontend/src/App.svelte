<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import { ModeWatcher } from 'mode-watcher';
  import Search from '$lib/components/Search.svelte';
</script>

<main>
  <Header />

  <Search/>
  <ModeWatcher />
</main>

<style>

</style>
