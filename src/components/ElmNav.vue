<template>
  <div class="nav border-bottom">
    <router-link to="/"><div>商品</div></router-link>
    <router-link to="/rating"><div>评价</div></router-link>
    <router-link to="/seller"><div>商家</div></router-link>
  </div>
</template>

<script>
export default {
  name: 'ElmNav'
}
</script>

<style lang="stylus" scoped>
    .nav
        display :flex
        flex-direction :row
        text-align :center
        height :.8rem
        line-height :.56rem
        font-size :.4rem
        & > a
            display :block
            flex :1
            color :#777
        .router-link-exact-active
            color :rgb(240,20,20)
</style>
