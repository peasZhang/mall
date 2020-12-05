<template>
  <div>
    <tabbar>
      <tabbaritem path="/home" itemname="首页">
        <img slot="item-icon" src="../../assets/img/tabbar/home.png">
        <img slot="item-icon-active" src="../../assets/img/tabbar/home_active.png">
        <div slot="item-text"></div>
      </tabbaritem>
      <tabbaritem path="/category" itemname="分类">
        <img slot="item-icon" src="../../assets/img/tabbar/category.png">
        <img slot="item-icon-active" src="../../assets/img/tabbar/category_active.png">
        <div slot="item-text"></div>
      </tabbaritem>
      <tabbaritem path="/shopcart" itemname="购物车">
        <img slot="item-icon" src="../../assets/img/tabbar/shopcart.png">
        <img slot="item-icon-active" src="../../assets/img/tabbar/shopcart_active.png">
        <div slot="item-text"></div>
      </tabbaritem>
      <tabbaritem path="/profile" itemname="个人">
        <img slot="item-icon" src="../../assets/img/tabbar/profile.png">
        <img slot="item-icon-active" src="../../assets/img/tabbar/profile_active.png">
        <div slot="item-text"></div>
      </tabbaritem>
    </tabbar>
  </div>
</template>

<script>
import tabbar from "./Tabbar"
import tabbaritem from "./TabbarItem"
export default {
  name: "mainTabbar",
  components: {
    tabbar,
    tabbaritem
  }
}
</script>

<style scoped>

</style>