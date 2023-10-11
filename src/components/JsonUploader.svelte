<h1 class="json-uploader__title">JSON Tree Viewer</h1>

<p class="json-uploader__subtitle">Simple JSON Viewer that runs completely on-client. No data exchange </p>

<button on:click={uploadFile}>
  Load JSON
</button>

{#if error}
  <p class="json-uploader__error">Invalid file. Please load a valid JSON file.</p>
{/if}

<script>
  let error = false;
  let file = null;

	const uploadFile = () => {
		console.log('uploading file')
	}
</script>

<style>
  .json-uploader__subtitle {
    margin: 20px 0;
  }

  .json-uploader__title {
    margin: 0;
  }

  .json-uploader__error {
    /* display: none; */
    color: red;
  }
</style>

