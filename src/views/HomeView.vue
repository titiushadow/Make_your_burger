<template>
<Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
     <BurgerForm />
   
  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import BurgerForm from "../components/BurgerForm.vue"

export default {
  nome: "Home",
  components: {
    Banner,
    BurgerForm  
  }
}
</script>
