<template>
  <div>
    <router-view></router-view>
    <service-bar></service-bar>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import ServiceBar from './../components/ServiceBar'
import NavFooter from './../components/NavFooter'
export default {
  name: 'order',
  components: {
    ServiceBar,
    NavFooter,
},
  data() {
    return {
      
    }
},
//生命周期 - 挂载完成（访问DOM元素）
  mounted() {
    
  }
}
</script>

<style scoped>
/* @import url(); 引入css类 */

</style>