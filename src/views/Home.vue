<template>
  <v-container>
    <h1 class="text-center">Lista de Cursos Disponibles</h1>
  <Card/>
  </v-container>
</template>

<script>
  
  import Card from '@/components/Card.vue'
  export default {
    name: 'Home-comp',

    components: {
      Card
    },
  }
</script>

<style scoped>

</style>