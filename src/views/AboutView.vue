<template>
  <div>
    <NavBar />
    <AboutComp />
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import AboutComp from '@/components/AboutComp.vue'
  export default {
    name: 'AboutView',
    components : {
      NavBar,
      AboutComp
    }
  }
</script>

<style scoped>

</style>