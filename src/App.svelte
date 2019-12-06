

<script>
	import SUM from "./sum.svelte"
	let src = '';
	let name = 'Rick Astley';
</script>
<input type="text" bind:value={src}>

<img {src} alt="{name} dances.">
<br/>
<SUM/>