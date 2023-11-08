<script lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import Navbar from './components/navbar.vue';


  export default {
    components:{
      Navbar
    }
  }

</script>

<template>
  <Navbar/>
  <RouterView />
</template>

<style scoped>

</style>
