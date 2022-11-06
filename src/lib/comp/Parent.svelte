<script lang="ts">
  import Son from './Son.svelte';

  let person = {
    name: '飞叶',
    age: 31,
  }

  const onSonBtnClick = (evt) => {
      person.name = evt.detail;
  }
</script>

<div class="parent">
  <Son {person} on:btn-click={onSonBtnClick}></Son>
</div>

<style>

</style>
