<template>
 <div class=" py-5 bg-dark " >
      <div class="d-flex flex-wrap ">
        <div class="col-12 col-md">
          <img src="../../img/Logo.png">
          <small class="d-block mb-3 text-muted">© 2021</small>
        </div>
        <div class="col-4 col-md">
          <h5 class="text-light">Features</h5>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugiat aspernatur accusamus inventore, consequuntur sapiente in veritatis quidem ducimus magni non nisi sequi nam nobis beatae quam explicabo blanditiis. Magnam, voluptate.</p>
        </div>
        <div class="col-4 col-md">
          <h5 class="text-light">Resources</h5>
          <ul class="list-unstyled text-small">
            <li><router-link class="text-muted" to="/">Home</router-link></li>
            <li><router-link class="text-muted" to="/about">Servicios</router-link></li>
            <li><a class="text-muted" href="#">Another resource</a></li>
            <li><a class="text-muted" href="#">Final resource</a></li>
          </ul>
        </div>
        <div  class="col-4 col-md">
          <animacion></animacion>
        </div>
        
      </div>
      </div>
</template>

<script>
 
  export default {
    name: 'footer',
  
  };
</script>