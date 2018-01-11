<template>
  <div class="box">
    <slot></slot>
  </div>
</template>

<script>
  export default {

  }
</script>

<style>
  .box {
    width: 200px;
    background-color: lightblue;
    border: 1px solid gray;
    padding: 10px;
    margin: 20px auto;
  }
</style>
