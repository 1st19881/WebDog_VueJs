<template>
    <div id="nav111">
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">dogilike</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
         <router-link to="/" class="nav-link " >หน้าแรก</router-link>
        </li>
       <li class="nav-item">
         <router-link to="/demo1" class="nav-link " >บทความ</router-link>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="#">เกี่ยวกับเรา</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">ติดต่อ</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
    </div>
</template>

<script>
export default {
  name: 'Navbar',
  data(){
    return{
     
    }
  }
}
</script>

<style scoped>
#nav111{
  margin-bottom:80px;
}
</style>