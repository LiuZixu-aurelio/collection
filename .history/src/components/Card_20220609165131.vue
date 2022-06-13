<template>
  <div @click="openweb" class="cardin">
    <img :src="logo" alt="无法显示">
    <div class="text1"><span>{{msg}}</span></div> 
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
.cardin {
  width: 150px;
  height: 46px;
  padding: 8px;
  border-radius: 8px;
  box-shadow: 1px 1px 2px 1px rgba(0, 0, 0, .1)
}
img {
  width: 32px;
  height: 32px;
  position: relative;
  top: 6px;
  margin-left: 8px;
}
span {
  position: relative;
  top: 0px;
  margin-left: 16px;
  font-size: 20px;
  font-weight: 800;
}
.text1 {
  justify-content: center;
}
</style>
