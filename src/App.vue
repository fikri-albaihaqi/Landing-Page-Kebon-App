<template>
<div class="container">
  <Navigation />
  <Header />
  <Features />
  <Sites />
  <Benefits />
  <Download />
  <Footer />
</div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Header from './components/Header.vue'
import Features from './components/Features.vue'
import Sites from './components/Sites.vue'
import Benefits from './components/Benefits.vue'
import Download from './components/Download.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    Header,
    Features,
    Sites,
    Benefits,
    Download,
    Footer
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

h1 {
  color: #202C44;
}
</style>
