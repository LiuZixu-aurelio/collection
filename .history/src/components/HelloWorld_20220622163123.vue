<template>
  <div>
    <div>
      <h2>搜索工具</h2>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='card' msg="pinterest" web="https://dribbble.com/" logo="https://s.pinimg.com/images/favicon_red_192.png"/>
      <Card class='card' msg="dribbble" web="https://it.pinterest.com/" logo="https://cdn.dribbble.com/assets/favicon-b38525134603b9513174ec887944bde1a869eb6cd414f4d640ee48ab2a15a26b.ico"/>
      <Card class='card' msg="站酷" web="https://www.zcool.com.cn/" logo="https://static.zcool.cn/git_z/z/site/favicon.ico?version=1618914637608"/>
      <Card class='card' msg="花瓣" web="https://huaban.com/" logo="https://huaban.com/favicon.ico"/>
      <Card class='card' msg="UI中国" web="https://www.ui.cn/" logo="https://www.ui.cn/favicon.ico"/>
      <Card class='card' msg="Color Hunt" web="https://colorhunt.co/" logo="https://colorhunt.co/img/colorhunt-favicon.svg?2"/>
      <Card class='card' msg="mapbox" web="https://api.mapbox.com/styles/v1/mapbox/light-v10.html?title=true&access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4M29iazA2Z2gycXA4N2pmbDZmangifQ.-g_vE53SD2WrJ6tFX7QHmA#13.52/47.50887/19.08254" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="样机世界" web="https://www.mockupworld.co/all-mockups/" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="插画 blush" web="https://blush.design/zh-CN?ref=producthunt" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="3d插画" web="https://3ddd.casa/" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="觅元素" web="http://www.51yuansu.com/" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="照片 500px" web="https://500px.com/popular" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      
      <h2>图标</h2>
      <Card class='card' msg="tablericons " web="https://tablericons.com/" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="remixicon " web="https://remixicon.com/" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="iconpark " web="https://iconpark.oceanengine.com/official" logo="https://static-assets.mapbox.com/branding/favicon/v1/favicon.ico?v=gAd4JjrGWl"/>
      <Card class='card' msg="iconfont " web="https://www.iconfont.cn/" logo="https://img.alicdn.com/imgextra/i2/O1CN01ZyAlrn1MwaMhqz36G_!!6000000001499-73-tps-64-64.ico"/>


      <h2>设计规范</h2>
      <Card class='card' msg="Ant Design" web="https://ant.design/" logo="https://gw.alipayobjects.com/zos/rmsportal/rlpTLlbMzTNYuZGGCVYM.png"/>
      <Card class='card' msg="Element" web="https://element-plus.gitee.io/zh-CN/#/zh-CN" logo="https://element-plus.gitee.io/apple-touch-icon.png"/>
      <Card class='card' msg="飞书" web="https://open.feishu.cn/document/uYjL24iN/ukjNzUjL5YzM14SO2MTN" logo="https://s3-imfile.feishucdn.com/static-resource/v1/1941d42c-fccc-44bb-bfcc-854d71b7ed3g"/>
      <Card class='card' msg="material" web="https://www.material.io/" logo="https://static.tdesign.tencent.com/favicon.ico"/>
      <Card class='card' msg="华为鸿蒙" web="https://developer.harmonyos.com/cn/design" logo="https://developer.harmonyos.com/assets/image/favicon.ico?v=202206062122"/>
      <Card class='card' msg="腾讯" web="https://tdesign.tencent.com/" logo="https://static.tdesign.tencent.com/favicon.ico"/>
      <Card class='card' msg="苹果" web="https://developer.apple.com/cn/design/" logo="https://developer.apple.com/apple-logo.svg"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>

      <h2>知识</h2>
      <Card class='card' msg="语雀 b端" web="https://www.yuque.com/sardine/lvdo4s" logo="https://gw.alipayobjects.com/mdn/prod_resou/afts/img/A*CUIoT4xopNYAAAAAAAAAAABkARQnAQ"/>
      <Card class='card' msg="石墨 b端" web="https://shimo.im/docs/kcndgcoA0skbv6Jh/read" logo="https://as.smvm.cn/from_qbox/favicon.ico"/>
    
    </div>
  </div>
</template>

<script>

import Card from './Card.vue'
export default {
  components: { Card },
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card {
  display:inline-block;
  margin: 16px;
}
h2 {
  left: 16px;
  position: relative;
  margin: 24px 0px 0px 0px;
}

</style>
