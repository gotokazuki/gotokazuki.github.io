<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="prose prose-lg mx-auto p-6">
  {@render children()}
</div>
