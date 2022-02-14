<template>
<div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img :src="img1" class="d-block w-100" :height="height" alt="...">
    </div>
    <div class="carousel-item">
      <img :src="img2" class="d-block w-100" :height="height" alt="...">
    </div>
    <div class="carousel-item">
      <img :src="img3" class="d-block w-100"  :height="height" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</template>

<script>
export default {
  name: 'Slide',
  data(){
    return{
      img1:"https://images.unsplash.com/photo-1512341350577-a09358311cb1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80",
      img2:"https://images.unsplash.com/photo-1593874105671-d745ff7ce8ba?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80",
      img3:"https://images.unsplash.com/photo-1612957775937-8157953886f5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80",
      // height:650
    }
  }
}
</script>

<style >
.carousel-item{
  height: auto;
}
</style>
