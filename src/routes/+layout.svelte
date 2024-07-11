<script>
	import { applyAction } from '$app/forms';

  import "../app.css";
  let {children} = $props();

</script>



{#if children}
  {@render children()}
{:else}
   <h1>No existe una página principo</h1>
{/if}



