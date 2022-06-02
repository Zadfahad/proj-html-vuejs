<template>
   <div class="ms_header-container">
      
    <!-- HEADER -->
    <header class="pt-2 mb-5 ">
      
     
        <!-- header btn -->
       
       
        <!-- header btn -->

        <!-- header nav -->
        <nav class="navbar navbar-expand-lg navbar-light">
  <div class="container-fluid ">
    
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
           <ul class="navbar-nav">
               <li class="nav-item pt-4">
                   <a class="ms_btn ms_btn-orange" href="">order online</a>
               </li>
                <li class="nav-item pt-3">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
         <li class="nav-item pt-3">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
         <li class="nav-item pt-3">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
        <img class="ms_logo mx-auto" src="../img/h5-logo-divided-header.png" alt="">
        
           <li class="nav-item pt-3 me-5">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
         <li class="nav-item pt-3 me-5">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
          <li class="nav-item pt-3 me-5">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
        </ul> 
     
      <ul class="navbar-nav pb-3">
           <li class="nav-item">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
         <li class="nav-item">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
        
        <!-- /header nav -->
   
    </header>
    <!-- /HEADER -->

    <!-- JUMBOTRON -->

    <div class="jumbotron">
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner jumbotron-img">
    <div class="carousel-item active">
      <img class="d-block w-100" src="../img/h3-rev-img-6.png" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../img/h3-rev-img-2.png" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../img/h3-rev-img-4.png" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
    </div>
    
    <!-- /JUMBOTRON -->

    <!-- MINI JUMBOTRONS -->
    <div class="mini-jumbos">
      <div class="ms_container">
        <div class="container-fluid">
          <div class="row  row-cols-lg-4 g-2">
            <div class="col ">
              <img src="../img/h3-img-1.jpg" alt="" />
            </div>
            <div class="col">
              <img
                src="../img/h3-img-2.jpg" alt=""/>
            </div>
            <div class="col">
              <img src="../img/h3-img-3.jpg" alt="" />
            </div>
            <div class="col">
              <img
                src="../img/h3-img-4.jpg" alt=""/>
            </div>
            
            
          </div>
        </div>
      </div>
    </div>
    <div class="reviews">
      <div class="ms_container pt-3 bg-white">
        <div class="container-fluid">
          <div class="row">
            <img src="../img/h3-testimonials-bckgrnd.jpg" alt="">
            <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      
    </div>
    <div class="carousel-item">
      
    </div>
    <div class="carousel-item">
      
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
          </div>
          
        </div>
      </div>
    </div>
    <!-- /MINI JUMBOTRONS -->
  </div>
</template>

<script>
export default {
    name: "AppHeader",

}
</script>

<style lang="scss" scoped>
.ms_header-container{
    width: 100%;
    background-color: black;
    .mini-jumbos{
        background-color: white;
    }

    
    header {
    width: 80%;
     background-color: black;
    
    margin: auto;
   
    
    
    .ms_logo {
      text-align: center;
      width:15%;
    }
    
   
}
.jumbotron-img{
    width: 20%;
    
}

}

</style>