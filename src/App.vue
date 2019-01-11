<template>
<div id="app">
  <router-view/>
  <footer-guide v-show="$route.meta.showFooter"/>

</div>
</template>

<script>
import FooterGuide from './components/FooterGuide/FooterGuide.vue'
export default {
  name: 'App',
  components: {
    FooterGuide
  }
}
</script>

export default {}

<style lang="stylus" rel="stylesheet/stylus">
  .app
    color:red
</style>
