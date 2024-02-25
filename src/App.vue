<template>
  <NavBar></NavBar>
  <router-view/>
  <Footer></Footer>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  components: {
    NavBar,
    Footer
  }
}
</script>

