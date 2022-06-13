<template>
  <div @click="openweb">
    <img :src="logo" alt="<!--  -->">
    <span>{{msg}}</span>
  </div>
</template>

<script>

export default {
  name: 'Card',
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
}
</style>
