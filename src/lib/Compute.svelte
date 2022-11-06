<script lang="ts">
// 计算属性
let a = 10;
$: b = a * 2;

setTimeout(() => {
    a = 30
}, 2000)
</script>

<div>
  {b}
</div>

<style>

</style>
