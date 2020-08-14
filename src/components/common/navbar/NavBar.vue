<template>
  <div class="nav-bar">
    <div class="left"><slot name="nav-left"></slot></div>
    <div class="center"><slot name="nav-center"></slot></div>
    <div class="right"><slot name="nav-right"></slot></div>
  </div>
</template>>

<script>
export default {
  name:'NavBar'
}
</script>

<style >
 .nav-bar{
    display: flex;
   
    height: 44px;
    line-height: 44px;
    text-align: center;
  }
  .left,.right{
    width: 45px;
    height: 44px;
  }
  .left{
    position: left;
  }
  .right{
    position: right;
  }
  .center{
    flex: 1;
  }
</style>