<template>
  <div class="warpper-container">
    <swiper :list="demo01_list" auto height="230px" v-model="demo01_index" @on-index-change="demo01_onIndexChange"></swiper>
    <grid>
      <grid-item link="/component/cell" label="活动公告">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg1.png">
      </grid-item>
      <grid-item link="" label="在线购卡">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg2.png">
      </grid-item>
      <grid-item link="/component/cell" label="在线商城">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg3.png">
      </grid-item>
    </grid>
    <grid>
      <grid-item link="/component/cell" label="特色课程">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg4.png">
      </grid-item>
      <grid-item link="" label="私教预约">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg5.png">
      </grid-item>
      <grid-item link="/component/cell" label="老师介绍">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg6.png">
      </grid-item>
    </grid>
    <grid>
      <grid-item link="/component/cell" label="在线请假">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg7.png">
      </grid-item>
      <grid-item link="" label="联系我们">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg8.png">
      </grid-item>
      <grid-item link="/component/cell" label="我要体验">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg9.png">
      </grid-item>
    </grid>
    <grid>
      <grid-item link="/component/cell" label="我要砍价">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg10.png">
      </grid-item>
      <grid-item link="" label="证书查询">
        <img slot="icon" src="http://static.7hu.cn/huxiaoer/image/common/icon_bg12.png">
      </grid-item>
    </grid>
  </div>
</template>

<script>
import { Scroller, Swiper, GroupTitle, SwiperItem, Grid, GridItem } from 'vux'

const baseList = [{
  url: 'javascript:;',
  img: 'http://image.kmbear.com/group1/M00/00/06/rB8AClj_FGaAcs82AAEdjNvFezk701.jpg',
  title: ''
}, {
  url: 'javascript:;',
  img: 'http://image.kmbear.com/group1/M00/00/05/rB8AClj-sWeAVXvdAACGcY_KVdw157.jpg',
  title: ''
}, {
  url: 'javascript:;',
  img: 'http://image.kmbear.com/group1/M00/00/06/rB8AClkAQZSARQcgAAETXgXmapc604.jpg',
  title: ''
}]
export default {
  components: {
    Swiper,
    SwiperItem,
    GroupTitle,
    Grid,
    GridItem,
  },
  data () {
    return {
      demo01_list: baseList,
    }
  }
}
</script>

<style>

</style>
