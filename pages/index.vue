<template>
  <div class="" >
    <div>  
      <Nav />

      <Inicio/>
      
      <NotaUno/>
      <Videos />

      <NotaDos/>
      <Artistas />
  
      <NotaTres />
      <Footer />
    </div>
  </div>
</template>

<script>
import Inicio from "~/components/Inicio.vue";
import Videos from "~/components/Videos.vue";
import NotaTres from "~/components/NotaTres.vue";
import NotaDos from "~/components/NotaDos.vue";

import Artistas from "~/components/Artistas.vue";
import Footer from "~/components/Footer.vue";
import Nav from "~/components/Nav.vue";
import NotaUno from "~/components/NotaUno.vue";



export default {
  components: {
    Inicio,
    Videos,
    NotaTres,
    Artistas,
    Footer, Nav, NotaUno, NotaDos
  },
};
</script>
