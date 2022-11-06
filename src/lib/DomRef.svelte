<script lang="ts">
// dom引用
import { onMount } from 'svelte';
let inputEl;
onMount(() => {
  inputEl.focus();
})
</script>

<div>
  <input type="text" value="feiye" bind:this={inputEl}>
</div>

<style>

</style>
