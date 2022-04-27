<template>
  <div class="row center-sm">
    <div class="col-sm-8 col-md-4 col-lg-3">
      <button class="btn-01">¿Qué puedo hacer?</button>
    </div>
    <div class="col-sm-8 col-md-4 col-lg-3">
      <button class="btn-02">Recomendaciones Vacaciones</button>
    </div>
    <div class="col-sm-8 col-md-4 col-lg-3">
      <button class="btn-03">Beneficios</button>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
button {
  border-radius: 4px;
  border: none;
  cursor: pointer;
  font-family: "Open Sans", sans-serif;
  font-style: normal;
  font-size: 14px;
  /* line-height: 22px; */
  color: white;
  padding: 0.5rem;
  box-shadow: 0 4px 2px -2px gray;
  width: 100%;
  margin-bottom: 1rem;
  
}
.btn-01 {
  background-color: #f7393b;

}
.btn-02 {
  background-color: #007abe;
}
.btn-03 {
  background-color: #00a957;
}
.btn-01:hover {
  background-color: #f90001;
}
.btn-02:hover {
  background-color: #006ca8;
}
.btn-03:hover {
  background-color: #01924b;
}
.row .center-sm{
    margin-top: 2rem
}
@media (min-width: 1024px) {
  .btn-01,.btn-02,.btn-03{
         width: 90%;
         height: 3rem;
  } 
}
@media (min-width: 1440px) {
  .btn-01,.btn-02,.btn-03{
         width: 80%;
         
  } 
}
</style>
