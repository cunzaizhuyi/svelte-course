<script lang="ts">
// 事件

let count = 0;

const add = () => {
  count++;
}
</script>

<div>
  <button on:click={add}>
    { count }
  </button>
</div>

<style>

</style>
