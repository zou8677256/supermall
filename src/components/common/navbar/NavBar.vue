<template>
  <div class="nav-bar">
    <div class="left"><slot name="left"></slot></div>
     <div class="center"><slot name="center"></slot></div>
      <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>
</script>

<style>
  .nav-bar{
    display: flex;
    line-height: 44px;
  }
  .left,.right{
    width: 60px;
    background-color: red;
  }
  .center{
    flex: 1;
    background-color: blue;
  }
</style>
