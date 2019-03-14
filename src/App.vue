<template>
  <div id="app">
    <!-- 头部 -->
    <v-header ></v-header>
    
  </div>
</template>

<script>
//引入头部组件
import VHeader from 'components/v-header/v-header'


export default {
  name: 'app',
  components: {
    "v-header":VHeader
  }
}
</script>
<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>
