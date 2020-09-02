<template>
  <div class="animate__animated animate__fadeIn">
    <div>  
      <Nav />

      <Inicio />
      <Videos />
      <Contacto />
      <About />
      <Footer />
    </div>
  </div>
</template>

<script>
import Inicio from "~/components/Inicio.vue";
import Videos from "~/components/Videos.vue";
import About from "~/components/About.vue";
import Contacto from "~/components/Contacto.vue";
import Footer from "~/components/Footer.vue";
import Nav from "~/components/Nav.vue";


export default {
  components: {
    Inicio,
    Videos,
    About,
    Contacto,
    Footer, Nav
  },
};
</script>
