<template>
  <swiper :options="swiperOption">
    <!-- slides -->
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1710/f5/57137c621d75ba02.jpg_640x200_b984ddf7.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1609/15/630b82d932a3c402.jpg_640x200_862e836b.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1711/b3/66f7230d9ad6e002.jpg_640x200_077e61ee.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1710/16/1d7693c6bd8abd02.png_640x200_43c308dd.png" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1609/c9/cacbf705c5417e02.jpg_640x200_99b2676a.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1609/f3/52a119dbed871902.jpg_640x200_b4573df8.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1711/c5/2b4166f592b33202.jpg_640x200_27b41388.jpg" alt="">
      </a></swiper-slide>
    <swiper-slide>
      <a href="" class="swiper-mark">
          <img class="swiper-Img" src="http://img1.qunarzz.com/piao/fusion/1703/51/01864a8a35c20402.jpg_640x200_d16dcbcd.jpg" alt="">
      </a></swiper-slide>
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</template>

<script>
  // swiper options example:
  export default {
    name: 'carrousel',
    data() {
      return {
        swiperOption: {
          autoplay: 3000,
          direction: 'horizontal',
          grabCursor: true,
          setWrapperSize: true,
          autoHeight: true,
          pagination: '.swiper-pagination',
          paginationClickable: true,
          mousewheelControl: true,
          observeParents: true,
        }
      }
    }
  }
</script>

<style>
  
  .swiper-mark{
    width:100%;
    height: 0;
    padding-bottom: 32%
  }

  .swiper-Img{
    width: 100%; 
  }
</style>