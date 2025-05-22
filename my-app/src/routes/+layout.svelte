<script>
  let { children } = $props();
  import "../app.css";
</script>
<style>
  :global(body) {
    font-family: 'Alegreya Sans', sans-serif;
  }
</style>
{@render children()}