<template>
  <div>
  <nav class="navbar navbar-expand-lg navbar-dark " style="background-color: rgb(46, 204, 113 )">
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/"><img src="../../img/Logo.png" alt="" style="width: 250px"></router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link"  to="/">Inicio</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/servicios">Servicios</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Noticias</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Iniciar sesión</a>
          </li>

        </ul>
        
      </div>
      <div style=" width: 20%; " class="d-sm-none d-md-block">
                <img  style=" height: 60px; " src="../../img/logomision.png" alt="Logo MisionTic 2022">
            </div>
    </div>
  </nav>
  </div>
</template>

<script>

export default {
    name: 'Navbar'
}
</script>


<style>

</style>