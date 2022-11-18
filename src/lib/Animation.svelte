<script lang="ts">
// 一个div不断改变大小的动画
let isHasAni = false;
setTimeout(() => {
  isHasAni = true;
}, 2000)
</script>

<div class="fy" style="animation: ani 2s infinite">
飞叶
</div>

<style lang="scss">
  @keyframes ani {
    0%{
      transform: scale(1);
    }
    100%{
      transform: scale(1.5);
    }
  }
  .ani{
    animation: ani 2s infinite;
  }
.fy{
  width: 100px;
  height: 100px;
  border: 1px solid #ccc;
}
</style>