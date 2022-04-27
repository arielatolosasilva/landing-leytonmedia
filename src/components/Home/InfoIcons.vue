<template>
  <div class="container">
      <div>
    <p class="title-01">Descarga la App BCI Móvil</p>
    <p class="title-02">
      y vive la experiencia de llevar tu banco a todas partes.
    </p>
    </div>
    <div class="row center-sm row01">
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon1.svg" class="icon" />
          <p class="text">Saldo</p>
        </div>
      </div>
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon2.svg" class="icon" />
          <p class="text">Transferencias</p>
        </div>
      </div>
       <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon3.svg" class="icon" />
          <p class="text">Pagos</p>
        </div>
      </div>
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon4.svg" class="icon" />
          <p class="text">Créditos</p>
        </div>
      </div>
    </div>
      <div class="row center-sm">
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon5.svg" class="icon" />
          <p class="text">Tarjetas</p>
        </div>
      </div>
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon6.svg" class="icon" />
          <p class="text">Seguros</p>
        </div>
      </div>
       <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon7.svg" class="icon" />
          <p class="text">Cajeros y Sucursales</p>
        </div>
      </div>
      <div class="col-sm-5 col-md-2">
        <div class="container-icon">
          <img src="../../assets/icon8.svg" class="icon" />
          <p class="text">Más servicios</p>
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
  margin-top: 2rem;
  
}
.title-01,
.title-02,.text {
  font-family: "Open Sans", sans-serif;
  font-style: normal;
  text-align: center;
}
.title-01 {
  font-weight: 800;

  color: #f73939;
}
.title-02,.text {
  font-weight: 600;
}
.text {
    font-size:12px;
    margin-bottom: .5rem
}
.container-icon,.icon{
    width: 90%;
}
.icon{
    width: 80%;
    
}
.row01{
    margin-top: 1.5rem
}
@media (min-width: 768px) {
  .icon{
    width: 50%;
    
}
}
@media (min-width: 1024px) {
.container {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    height: 80%;
        
}
}

</style>
