<template>
    <div id="tab-bar">
      <slot> </slot>
    </div>
</template>


<script>
export default {
  name:'TabBar'
}
</script>


<style scoped>
  #tab-bar{
    height: 49px;
    background-color: #fff;
    display: flex;
    position: fixed;
    bottom: 0;
    right: 0;
    left: 0;
    border-top: 1px solid #ccc;
  }
</style>