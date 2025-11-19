<template>
  <div>
    <Navbar />
    <Hero />
    <Overview />
    <Footer />
  </div>
</template>

<script>
import Navbar from './Navbar.vue'
import Hero from './Hero.vue'
import Overview from './Overview.vue'
import Footer from './Footer.vue'

export default {
  name: 'HomePage',
  components: {
    Navbar,
    Hero,
    Overview,
    Footer
  }
}
</script>