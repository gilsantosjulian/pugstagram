<script>
  import Header from '../components/Header.svelte';
  import Timeline from '../components/Timeline.svelte';
  import Main from '../components/Main.svelte';
  import Sidebar from '../components/Sidebar.svelte';
</script>

<style>
  :global(body) {
    background-color: #676778;
    color: white;
  }
</style>

<Header />

<Main>
  <Timeline />
  <Sidebar /> 
</Main>