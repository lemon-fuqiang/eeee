<template>
<div id="home">
  <nav-bar class="home-nav"> 
    <div  slot="nav-center">购物街</div>
  </nav-bar>
</div>
  
</template>>

<script >


import NavBar from 'components/common/navbar/NavBar'
export default ({
  name:'Home',
  components: {
    NavBar
  }
})
</script>



<style >
  .home-nav{
    background-color: pink;
    height: 44px;
  }
</style>