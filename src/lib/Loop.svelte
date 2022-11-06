<script lang="ts">
// 列表渲染

let arr = ['red', 'green', 'blue']

setTimeout(() => {
    arr = [];
}, 2000)

</script>

<div>
  <ul>
    {#each arr as item, index}
      <li>{index + 1} - {item}</li>
    {:else}
      列表为空
    {/each}
  </ul>
</div>

<style>

</style>
