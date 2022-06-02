<template>
  <footer>
      <div class="locations pt-2">
          <div class="row row-cols-lg3 g-0">
              <div class="col contacts">
                  <h5 class="text">find our Resturants</h5>
              </div>
              <div class="col contacts">
                  <h5 class="text">Working hours</h5>
              </div>
              <div class="col contacts">
                  <h5 class="textw">don pepe</h5>
              </div>
              <div class="col">
                  <img src="../img/footer-img-1.jpg" alt="">
              </div>
          </div>
      </div>

  </footer>
</template>

<script>
export default {
    name:"AppFooter",

}
</script>

<style lang="scss" scoped>
.locations{
    .contacts{
        background-color: black;
    .text{
        color: yellow;
    }
    .textw{
        color: white;
    }
    }
    
}

</style>