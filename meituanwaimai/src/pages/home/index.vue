<template>
  <div class="home">
    <search></search>
    <recommand></recommand>
  </div>
</template>

<script>
import search from "@/components/search/search";
import recommand from "@/components/recommand/recommand";

export default {
  components: {
    search,
    recommand
  }
};
</script>

<style lang="stylus" scoped>
.heard
        justify-content: space-around
        display flex
        width 100%
        height 80rpx
        background #FFC640
        .heard-location
            position relative
            font-size 25rpx
            padding 5rpx 15rpx
            margin 10rpx
            width 250rpx
            height 40rpx
            line-height 40rpx
            overflow hidden
            white-space nowrap
            text-overflow ellipsis
            background #B38B2D
            color white
            border-radius 20rpx
            &:after
                content ''
                position absolute
                top 20rpx
                left 250rpx
                width 8rpx
                height 8rpx
                border 3rpx solid #fff
                border-bottom none
                border-left none
                transform rotate(45deg)
            .heard-location-icon
                position absolute
                top 12rpx
                height 25rpx
                width 25rpx
            .heard-location-text
                left 47rpx
                height 30rpx
                width 190rpx
                padding-left 30rpx
              
        .heard-search
            font-size 25rpx
            padding 5rpx 15rpx
            margin 10rpx
            height 40rpx
            width 400rpx
            background white
            border-radius 20rpx
            line-height 40rpx
            .text
                padding-left 10rpx
                color #ccc
            .heard-search-icon
                height 21rpx
                width 21rpx
    

</style>
