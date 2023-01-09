<template>
  <div class="home">
    <NavBar />
    <HelloWorld />
    <Footer />
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import HelloWorld from '@/components/HelloWorld.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    HelloWorld,
    Footer
  }
}
</script>
