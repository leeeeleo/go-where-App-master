<template>
  <div class="header">
    <div class="header-left">
        <span class="iconfont back-icon">&#xe685;</span>
    </div>
    <div class="header-input">
        <span class="iconfont">&#xe67d;</span>
        输入城市/景点/游玩主题
    </div>
    <div class="header-r ight">
        城市
        <span class="iconfont arrow-icon">&#xe665;</span>
    </div>
  </div>
</template>

<script>
export default {
name:'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  @import '~@/assets/styles/varibles.styl'
  .header
    display: flex
    line-height: .86rem
    background: $bgColor
    color: #fff
    .header-left
      width .64rem
      float: left
      .back-icon
        text-align: center
        font-size:.4rem
    .header-input
      flex:1
      height: .64rem
      line-height: .64rem
      margin-top: .12rem
      margin-left: .2rem
      padding-left:.2rem
      background: #fff
      border-radius:5px
      color: #ccc
    .header-right
      width: 1.24rem
      float: right
      text-align: center
      .arrow-icon
        margin-left: -.1rem
        fon-size: .24rem
</style>