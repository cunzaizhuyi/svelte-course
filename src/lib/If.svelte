<script lang="ts">
// 条件渲染 if,  if else , if else if else if else

let isShowDialog = true;

let name = 'feiye';

let code = 404
</script>

<div>
  {#if isShowDialog}
    这里是对话框的UI
  {/if}

  <div>
    {#if name}
      你是{name}
    {:else}
      你是 默认用户
    {/if}
  </div>


  <div>
    {#if code === 302}
      重定向了302
    {:else if code === 307}
      重定向了307
    {:else if code === 404}
      页面找不到了
    {:else}
      成功返回
    {/if}
  </div>
</div>

<style>

</style>
