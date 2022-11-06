<script lang="ts">
  import Son from './Son.svelte';

</script>

<div class="parent">
  <Son>
    <h3>我是飞叶</h3>
    <div slot="footer">父组件定义的footer</div>
  </Son>
</div>

<style>

</style>
