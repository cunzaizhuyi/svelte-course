<script lang="ts">
// 事件参数

let count = 0;

const add = (event) => {
  console.log('111: ', event)
  count++;
}

const add2 = (cnt) => {
  count = cnt + 1;
}
</script>

<div>
  <button on:click={() => add()}>
    { count }
  </button>

  <button on:click={() => add2(count)}>
    { count }
  </button>
</div>

<style>

</style>
