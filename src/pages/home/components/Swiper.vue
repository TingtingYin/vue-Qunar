<template>
  <swiper :options="swiperOption" >
    <!-- slides -->
    <swiper-slide>
      <img class="swipe-img" src="http://img1.qunarzz.com/piao/fusion/1812/d6/daa880b254940402.jpg_750x200_b114308a.jpg">
    </swiper-slide>
    <swiper-slide>
    <img class="swipe-img" src="http://img1.qunarzz.com/piao/fusion/1811/31/da037478f37cf202.jpg_750x200_fe28d396.jpg">
    </swiper-slide>

    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>

  </swiper>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {}
    }
  }
}
</script >

<style lang="stylus" scoped>
 .swipe-img
    width: 100%
</style>
