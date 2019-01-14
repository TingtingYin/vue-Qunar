<template>
 <div class=wrapper>
  <swiper :options="swiperOption" >
    <swiper-slide>
      <img class="swipe-img" src="http://img1.qunarzz.com/piao/fusion/1812/d6/daa880b254940402.jpg_750x200_b114308a.jpg">
    </swiper-slide>
    <swiper-slide>
    <img class="swipe-img" src="http://img1.qunarzz.com/piao/fusion/1811/31/da037478f37cf202.jpg_750x200_fe28d396.jpg">
    </swiper-slide>

    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
 </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination'
      }
    }
  }
}
</script >

<style lang="stylus" scoped>
 .wrapper
  overflow: hidden
  width: 100%
  height: 0
  padding-bottom:27.25%
  .swipe-img
    width: 100%
</style>
