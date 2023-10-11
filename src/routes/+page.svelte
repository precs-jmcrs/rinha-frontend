<div class="json-tree-viewer">
  <JsonUploader />
</div>

<script>
  import JsonTreeRenderer from "../components/JsonTreeRenderer.svelte";
	import JsonUploader from "../components/JsonUploader.svelte";
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
  .json-tree-viewer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-family: 'Inter', sans-serif;
  }
</style>