<template>
  <!-- MAIN -->
    <main>
        <div class="specials">
      <div class="ms_container pt-3">
        <div class="container-fluid">
          <div class="row  row-cols-lg-2">
            <div class="col plus ">
              <img src="../img/h1-img-4.jpg" alt="" />
              <img class="plusimage" src="../img/h1-img-7n.png" alt="">
            </div>
           
            <div class="col">
                <h2>specials</h2>
             
            </div>
          
            
            
          </div>
        </div>
      </div>
    </div>
    <div class="banner">
        <div class="ms_container pt-2">
            <div class="container-fluid bimg-container">
                <div class="row">
                    <img class="bimg" src="../img/h3-background-img.jpg" alt="">
                </div>
            </div>
        </div>

    </div>
      <div class="mini-jumbos">
      <div class="ms_container pt-2">
        <div class="container-fluid">
          <div class="row  row-cols-lg-4 g-0">
            <div class="col ">
              <img src="../img/h1-team-1a-700x700.jpg" alt="" />
            </div>
            <div class="col">
              <img
                src="../img/h1-team-2a.jpg" alt=""/>
            </div>
            <div class="col">
              <img src="../img/h1-team-3a.jpg" alt="" />
            </div>
            <div class="col">
              <img
                src="../img/h1-team-4a.jpg" alt=""/>
            </div>
            
            
          </div>
        </div>
      </div>
    </div>
    <div class="options">
        <div class="ms_container pt-2">
            <div class="row row-cols-lg5">
                <div class="col ">
              <img src="../img/h1-clients-img-4.png" alt="" />
            </div>
            <div class="col ">
              <img src="../img/h1-clients-img-3.png" alt="" />
            </div>
            <div class="col ">
              <img src="../img/h1-clients-img-1.png" alt="" />
            </div>
            <div class="col ">
              <img src="../img/h1-clients-img-2.png" alt="" />
            </div>
            <div class="col ">
              <img src="../img/h1-clients-img-5.png" alt="" />
            </div>

            </div>
        </div>
    </div>
    <div class="menu">
        <div class="ms_container pt-2">
            <div class="row">
                <p class="text-center rtext">choose your flavour</p>
                <h3 class="text-center">THE BEST PIZZA MENU IN TOWN</h3>
                <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam dolores <br> ne obcaecati alias aus! Autem, voluptates!</p>

            </div>
            <div class="row row-cols-lg6 pt-3">

                 <div class="col ">
              <img src="../img/h3-product-img-1a-100x100.png" alt="" />
            </div>
             <div class="col ">
              <img src="../img/h3-product-img-2a-150x150.png" alt="" />
            </div>
             <div class="col ">
              <img src="../img/h3-product-img-3a-150x150.png" alt="" />
            </div>
             <div class="col ">
              <img src="../img/h3-product-img-4a-150x150.png" alt="" />
            </div>
             <div class="col ">
              <img src="../img/h3-product-img-5a-150x150.png" alt="" />
            </div>
             <div class="col ">
              <img src="../img/h3-product-img-6a-100x100.png" alt="" />
            </div>
                
            </div>
        </div>
    </div>
    <div class="deals">
        <div class="ms_container pt-5">
            <div class="row row-cols-lg2">
                <div class="col">
                    <h3>pizza </h3>
                </div>
                <div class="col">
                    <img src="../img/h3-img-5a.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
    <div class="orde">
        <div class="ms_container pt-2">
            <div class="row">
                <img src="../img/h3-background-img-3.jpg" alt="">
            </div>
        </div>
    </div>

    </main>
    
    <!-- /MAIN -->
  
</template>

<script>
export default {
    name:"AppMain",

}
</script>

<style lang="scss" scoped>
.specials{
    .plus {
    position: relative;
    display: block;
    .plusimage {
        width: 39%;
    left:37%;
    top: 29%;
    position: absolute;
    margin-top: -25px;
    margin-left: -25px;
}
}

}
main{
    .options{
        background-color: #f7f7f2;
    }
    .options img{
        width: 70%;
    }
}


</style>