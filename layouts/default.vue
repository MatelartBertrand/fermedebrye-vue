<template>
  <div>
    <navbar></navbar>
    <nuxt/>
    <fdbfooter></fdbfooter>
  </div>
</template>

<script>
  import Navbar from '@/components/Navbar.vue'
  import fdbfooter from '@/components/Footer.vue'
  export default {
    components: {
      Navbar,
      fdbfooter
    }
  }
</script>

<style>
</style>
