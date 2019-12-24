<template>
<Principal id=home>
  <div  class="texto">  
      Bem vindo ao Gaia
  </div>
</Principal>
</template>

<script>
import Principal from "../layouts/principal"

export default {
  name: 'app',
  components: { 
    Principal
  }
}
</script>

<style scoped>

 #home {
    background-image: url(../imgs/fo3.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
    font-family: 'Numans', sans-serif;
} 

.texto{
  margin-top: 50px;
  margin-left: 700px;
  color: white;
  font-size: 100px
}


  
</style>
