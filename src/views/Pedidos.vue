<template>
  <div class="main-container">
    <h1>Gerenciar pedidos:</h1>
    <Dashboard />
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard.vue'
export default {
   nome: "Pedidos",
   components: { 
    Dashboard  
  },
}
</script>
