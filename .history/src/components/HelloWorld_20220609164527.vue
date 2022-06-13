<template>
  <div>
    <div>
      <h2>工具</h2>
      <Card class='card' msg="百度" web="https://www.baidu.com" logo="https://www.baidu.com/favicon.ico"/>
      <Card class='dribbble' msg="百度" web="https://dribbble.com/" logo="https://dribbble.com/favicon.ico"/>
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
