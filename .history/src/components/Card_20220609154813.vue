<template>
  <div>
    <img src="" alt="">
    <span>{{msg}}</span>
    <span>{{web}}</span>
  </div>
</template>

<script>
import func from 'vue-editor-bridge'
export default {
  name: 'Card',

  props: {
    msg: String,
  },
  methods:{
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
