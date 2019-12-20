<template>
<Principal>
  <div class="home">  
    <img class="img-fluid banner" src="../imgs/fo3.jpg" />
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id temporibus, excepturi corporis omnis reiciendis nesciunt repudiandae ea beatae? Ut, obcaecati iusto nisi recusandae quod autem harum itaque quibusdam quam alias.</p>
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

<style>
.banner {
  width: 100%;
  max-height: 600px; 
}
/* .home {
    background-image: url(../imgs/fo3.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
    font-family: 'Numans', sans-serif;
} */


  
</style>
