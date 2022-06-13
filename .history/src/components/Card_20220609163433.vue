<template>
  <div @click="openweb">
    <img :src="logo" alt="无法显示">
    <span>{{msg}}</span>
  </div>
</template>

<script>

export default {
  name: 'Card',
  data: function(){
    return {

      }
  },
  props: {
    msg: String,
    web: String,
    logo: String
  },
  methods:{
    openweb:function(){
      window.open(this.web)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
  border: 1px solid red;
  width: 150px;
  height: 50px;
  padding: 8px;
}
img {
  width: 32px;
  height: 32px;
}
span {
  position: relative;
  top: 0px;
  margin-left: 8px;
}
</style>
