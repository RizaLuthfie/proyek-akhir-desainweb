<template>
  <div>
    <Navbar />
    <ContactHero />
    <ContactInfo />
    <Footer />
  </div>
</template>

<script>
import Navbar from './Navbar.vue'
import ContactHero from './ContactHero.vue'
import ContactInfo from './ContactInfo.vue'
import Footer from './Footer.vue'

export default {
  name: 'ContactPage',
  components: {
    Navbar,
    ContactHero,
    ContactInfo,
    Footer
  }
}
</script>