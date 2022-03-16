<template>
  <navbar/>
  <router-view/>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  components: { Navbar },
}

</script>


<style>
#app {
  font-family: System-ui;
  text-align: center;
}
* {
  margin: 0;
  padding: 0;
}
</style>
