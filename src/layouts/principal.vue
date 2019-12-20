<template>
  <div class>
    <Navbar></Navbar>
    <router-view></router-view>
    <article>
      <slot/>
    </article>
    <Footer />
  </div>
</template>

<script>
import Navbar from "../components/common/Navbar";
import Footer from "../components/common/footer";
export default {
  components: {
    Navbar, Footer
  }
};
</script>

<style scoped>
</style>