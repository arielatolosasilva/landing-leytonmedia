<template>
    <div class="container">
       <img src="../../assets/Component3.svg" alt="" class="img">
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.container{
    display: flex;
 
    align-items: center;
    justify-content: center;
    
}
.img{
        width: 100%;
    }
@media (min-width: 768px) {
    .img{
        width: 67%;
    }
}
@media (min-width: 1024px) {
    .img{
        width: 50%;
    }
}
</style>
