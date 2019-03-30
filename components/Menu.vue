<template>
  <div class="menu">
    <nuxt-link to="/">首页</nuxt-link>
    <nuxt-link to="/user">内页</nuxt-link>
  </div>
</template>

<script>
    export default {
        name: "Menu"
    }
</script>

<style scoped>
  .menu{
    position: absolute;background: orangered;width: 100%;height: 80px;left: 0;top:0;text-align: center;line-height: 60px;
  }
</style>
