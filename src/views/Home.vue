<template>
  <div>
    <carrucel></carrucel>
    <br>
    <h2 >Servicios</h2>
    <div class="  d-flex  flex-wrap bd-highlight pt-4">
    <servicios class="col-md-4 col-6 d-flex justify-content-center pt-4"></servicios>
    <servicios class="col-md-4 col-6 d-flex justify-content-center pt-4"></servicios>
    <servicios class="col-md-4 col-12 d-flex justify-content-center pt-4"></servicios>
    </div>
    <h2 class="pt-4">Noticias</h2>
    <div class=" d-flex flex-row pt-4">

    <noticiasinver class="col-md-6 col-12"></noticiasinver>
    <Noticias class="col-md-6  col-12"></Noticias>
    
    </div>
    <div class=" d-flex flex-row pt-4">

    <Noticiasinver class="col-md-6 col-12"></Noticiasinver>
    <Noticias class="col-md-6  col-12"></Noticias>
    
    </div>
    <noticiasinver class="col-md-6 col-12"></noticiasinver>
    
    <team></team>
  </div>
</template>

<script>
// @ is an alias to /src
import Noticias from '@/components/Noticias.vue'
import Carrucel from '../components/Carrucel.vue';
import Noticiasinver from '../components/Noticiasinver.vue';
import Servicios from '../components/servicios.vue';
import Team from '../components/team.vue';




export default {
  name: 'Home',
  components: {
    
    Carrucel,Noticias,
    Noticiasinver,
    Servicios, Team
  }
}

   </script>
