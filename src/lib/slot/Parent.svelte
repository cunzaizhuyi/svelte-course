<script lang="ts">
  import Son from './Son.svelte';

//  样式穿透问题  :global进行穿透  默认不穿透
</script>

<div class="parent">
  <Son>
    <h3>我是飞叶</h3>
    <div slot="footer">父组件定义的footer</div>
  </Son>
</div>

<style lang="scss">
.parent{
  background: gray;
  :global(.son){
    height: 300px;
  }
}
</style>
