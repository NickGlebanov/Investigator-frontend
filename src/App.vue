<template>
  <Header id="header"/>
  <router-view/>
</template>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 20px
  max-width 100%
  width 1650px
  margin-left auto
  margin-right auto

#header
  margin-bottom 20px
</style>
<script>
import Header from "@/components/Header";
export default {
  components: {Header}
}
</script>
