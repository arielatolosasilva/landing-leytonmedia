<template>
  <div class="container">
    <img src="../../assets/responsive.png" alt="" class="img" />
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.container{
    margin-top: 2rem;
    display: flex;
    justify-content: center;
}
.img {
  width: 100%;
 
}
@media (min-width: 1024px) {
 .img {
  width: 70%;
 
}
    
}
</style>
