<template>
  <div>
    <div>
      <h2>工具</h2>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='card' msg="dribbble" web="https://dribbble.com/" logo="https://cdn.dribbble.com/assets/favicon-b38525134603b9513174ec887944bde1a869eb6cd414f4d640ee48ab2a15a26b.ico"/>
      <Card class='card' msg="站酷" web="https://www.zcool.com.cn/" logo="https://static.zcool.cn/git_z/z/site/favicon.ico?version=1618914637608"/>
      <Card class='card' msg="花瓣" web="https://huaban.com/" logo="https://huaban.com/favicon.ico"/>
      <Card class='card' msg="UI中国" web="https://www.ui.cn/" logo="https://www.ui.cn/favicon.ico"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>

      <h2>设计规范</h2>
      <Card class='card' msg="Ant Design" web="https://ant.design/" logo="https://gw.alipayobjects.com/zos/rmsportal/rlpTLlbMzTNYuZGGCVYM.png"/>
      <Card class='card' msg="Element" web="https://element-plus.gitee.io/zh-CN/#/zh-CN" logo="https://element-plus.gitee.io/apple-touch-icon.png"/>
      <Card class='card' msg="飞书" web="https://open.feishu.cn/document/uYjL24iN/ukjNzUjL5YzM14SO2MTN" logo="https://open.feishu.cn/favicon.ico"/>
      <Card class='card' msg="material" web="https://www.material.io/" logo="https://www.material.io/favicon.ico"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
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

</style>
