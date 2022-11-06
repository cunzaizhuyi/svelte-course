<script lang="ts">
  import { createEventDispatcher } from 'svelte';

  const emit = createEventDispatcher();
export let person = {
  name: '',
  age: '',
}

const btnClick = () => {
  emit('btn-click', '飞叶_程序员2222222');
}
</script>

<div class="son">
  子组件
  <div>{ person.name }, {person.age}</div>
  <button on:click={btnClick}>点我</button>
</div>

<style>
.son{
    width: 200px;
    height: 100px;
    border: 1px solid #ccc;
}
</style>
