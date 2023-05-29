<template>
  <div class="home">
    <!-- 头部导航 -->
    <top-nav></top-nav>
    <!-- 轮播图 -->
    <swiper-com></swiper-com>
    <!-- icon列表 -->
    <icon-list></icon-list>
    <!-- 音乐列表 -->
    <music-list></music-list>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
<<<<<<< HEAD
import TopNav from '@/components/TopNav.vue'
import IconList from '@/components/IconList.vue'
import MusicList from '@/components/MusicList.vue'
import SwiperCom from '@/components/SwiperCom.vue'
=======
import topNav from '@/components/TopNav.vue'
import swiperCom from '@/components/SwiperCom.vue'
import iconList from '@/components/IconList.vue'
import musicList from '@/components/MusicList.vue'
>>>>>>> a807ee4b609b5613737e760da8e3284996ea4f5e

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
<<<<<<< HEAD
    TopNav,
    SwiperCom,
    IconList,
    MusicList
=======
    topNav,
    swiperCom,
    iconList,
    musicList
>>>>>>> a807ee4b609b5613737e760da8e3284996ea4f5e
  }
}
</script>

<style>
#d1{
  width: 3rem;
  height: 3rem;
  background: skyblue;
  font-size: 0.3rem;
}
</style>

