<script lang="ts">
// 事件

let count = 0;

const add = () => {
  count++;
}

const boxClick = () => {
    console.log('111: ')
}
</script>

<div on:click={boxClick}>
  <button on:click|stopPropagation={add}>
    { count }
  </button>
</div>

<style>

</style>
