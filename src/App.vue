<template>
<div>
  <v-app>
    <Navbar/>
    <v-main>
       <router-view></router-view>
    </v-main>
  </v-app>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'App',

  data: () => ({
    //
  }),
  components: {
    Navbar
  }
};
</script>

<style>

</style>