<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import { ModeWatcher } from 'mode-watcher';
  import Search from '$lib/components/Search.svelte';
  import Main from '$lib/components/Main.svelte';
</script>

<main>
  <Header />
  <Main/>
  <Search/>
  <ModeWatcher />
</main>

