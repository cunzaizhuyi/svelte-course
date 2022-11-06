<script lang="ts">

</script>

<div class="son">
  子组件
  <div>
    <slot>如果父组件不写内容，这里是子组件默认的UI</slot>
  </div>

  <div>
    <slot name="footer"></slot>
  </div>
</div>

<style>
.son{
    width: 200px;
    height: 150px;
    border: 1px solid #ccc;
}
</style>
