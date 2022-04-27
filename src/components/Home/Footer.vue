<template>
  <div class="container">
    <div class="title">
      <p class="text-title">
        ¡Estas vacaciones cuídate del Skimming o Clonacíon de Tarjetas!
      </p>
    </div>
    <div class="row">
      <div class="col-sm-6 col-md-3">
        <div class="row rows">
          <div class="col-sm-2">
            <img src="../../assets/creditcard-icon.png" alt="" class="img" />
          </div>
          <div class="col-sm-10">
            <p class="text-sub">Consejo 1 :</p>
            <p class="text-info">
              Realiza directamente tus transferencias o mantén tu tarjeta a la
              vista todo el tiempo.
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="row rows">
          <div class="col-sm-2">
            <img src="../../assets/hand-hide.png" alt="" class="img" />
          </div>
          <div class="col-sm-10">
            <p class="text-sub">Consejo 2 :</p>
            <p class="text-info">
              Cuando uses cajeros automáticos cubre con tu mano la contraseña.
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="row rows">
          <div class="col-sm-2">
            <img src="../../assets/no-pic-icon.png" alt="" class="img" />
          </div>

          <div class="col-sm-10">
            <p class="text-sub">Consejo 3 :</p>
    
            <p class="text-info">Nunca permitas que fotografien tus tarjetas.</p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="row rows">
          <div class="col-sm-2">
            <img src="../../assets/no-voice-icon.png" alt="" class="img" />
          </div>

          <div class="col-sm-10">
            <p class="text-sub">Consejo 4 :</p>
            
            <p class="text-info">No des nunca tu clave en voz alta.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.container {
  background-color: #32aed7;
  padding: 1rem;
  border-radius: 10px;
  margin-bottom: 2rem
}
.text-title,
.text-sub,.text-info {
  font-family: "Open Sans", sans-serif;
  font-style: normal;
  color: white;
  font-weight: 500;
  
}

.text-sub {
  font-size: 14px;
  text-align: start;
  margin-left:1rem
}
.text-info{
    font-size: 12px;
    text-align: start;
    
     margin:  0.5rem 0 0.8rem 0.5rem

    
}
img.img {
  width: 100%;
}
.title{
margin-bottom: 2rem
}
@media (min-width: 1600px) {
  .rows{
         width: 80%;
         
  } 
}
</style>
