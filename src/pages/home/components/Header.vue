<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩/主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe600;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
// 1rem = html font-size = 50px
.header
  background $bgColor
  line-height .86rem
  display flex
  color #fff
  height .86rem
  .header-left
    width .64rem
    float left
    .back-icon
      text-align center
      font-size .4rem
  .header-right
    width 1.24rem
    float right
    text-align center
    .arrow-icon
      margin-left -.04rem
      font-size .24rem
  .header-input
    flex 1
    height .64rem
    background #ffffff
    border-radius .1rem
    margin-top .12rem
    line-height .64rem
    margin-left .2rem
    color: #ccc
    padding-left .2rem
</style>
