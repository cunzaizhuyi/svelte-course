<script lang="ts">
// class 常见的两个需求：1. 根据某变量进行class切换  2. 满足某条件添加某class

let color = '2';

let hasName = false;
</script>

<div>
  <div class="{color === '1' ? 'a' : 'b'}">feiye</div>

  <div class:a = {hasName}>飞叶</div>
</div>

<style>
.a{
    color: red;
}
.b{
    color: green;
}
</style>
