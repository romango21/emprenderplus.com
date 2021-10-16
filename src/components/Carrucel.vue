<template>
<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators " style="z-index: 100">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../../img/emprender.png" class="d-block w-100" alt="¿como emprender?">
     <div class="carousel-caption d-md-block pb-2" style="  background-color: rgba(0, 0, 0, .4)">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../../img/trabajo.jpg" class="d-block w-100" alt="las nuevas tecnologias en el emprendimiento">
      <div class="carousel-caption  d-md-block pb-2" style="  background-color: rgba(0, 0, 0, .4)">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../../img/computadora.jpg" class="d-block w-100" alt="las nuevas tecnologias en el emprendimiento">
      <div class="carousel-caption  d-md-block pb-2" style="  background-color: rgba(0, 0, 0, .4)">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../../img/bombillo.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-md-block pb-2" style="  background-color: rgba(0, 0, 0, .4)">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
        
      </div>
       
    </div>
    
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>


</template>

<script>
export default {
 name:'Carrusel'
}
</script>


<style>

</style>