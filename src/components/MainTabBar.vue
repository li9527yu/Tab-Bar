<template>
  <tab-bar>
        <tab-bar-item path='/home' >
          <img slot="item-icon" src="../assets/img/home.png" alt="">
          <img slot="item-icon-active" src="../assets/img/home_active.png" alt="">  
          <div slot="item-text">首页</div>
        </tab-bar-item >

        <tab-bar-item path='/category'>
          <img slot="item-icon" src="../assets/img/category.png" alt=""> 
          <img slot="item-icon-active" src="../assets/img/category_active.png" alt=""> 
          <div slot="item-text">分类</div>
        </tab-bar-item>

        <tab-bar-item path='/shopcart'>
          <img slot="item-icon" src="../assets/img/shopcart.png" alt=""> 
          <img slot="item-icon-active" src="../assets/img/shopcart_active.png" alt=""> 
          <div slot="item-text">购物车</div>
        </tab-bar-item>

        <tab-bar-item path='/profile'>
          <img slot="item-icon" src="../assets/img/profile.png" alt=""> 
          <img slot="item-icon-active" src="../assets/img/profile_active.png" alt=""> 
          <div slot="item-text">我的</div>
        </tab-bar-item>
      </tab-bar>
</template>

<script>
import TabBar from './tabbar/Tabbar'
import TabBarItem from './tabbar/TabBarItem'
export default {
    name:'MainTabBar',
    components:{
        TabBar,
        TabBarItem
    }
}
</script>

<style>

</style>