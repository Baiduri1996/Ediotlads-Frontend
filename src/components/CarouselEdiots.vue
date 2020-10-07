<template>
  <!-- Carousel -->
  <div
    id="carouselExampleControls"
    class="carousel slide mb-2"
    data-ride="carousel"
  >
    <div class="container">
      <div class="carousel-inner">
        <carousel
          class="item-carousel"
          :items="1"
          :nav="false"
          :autoplay="true"
          :loop="true"
        >
          <div class="logo-item active">
            <div class="row pt-4 justify-content-center">
              <div class="col-9 col-sm-4 col-md-6 col-lg-4 pt-5 text-left">
                <h1 class="mb-3">Spesial Summer Sale!</h1>
                <p class="mb-4 ">
                  Spesial offer only on this summer sale get your outfit before
                  it sold.
                </p>
                <a href="#" class="btn btn-danger">Get it Now</a>
              </div>
              <div
                class="col-3 col-sm-6 col-md-4 col-lg-4 d-none d-sm-block offset-1"
              >
                <img
                  class="foto-item"
                  src="img/slideshow/laura-chouette-jtXhEaqbv-c-unsplash.png"
                />
              </div>
            </div>
          </div>

          <div class="logo-item">
            <div class="row pt-4 justify-content-center">
              <div class="col-9 col-sm-4 col-md-6 col-lg-4 pt-5 text-left">
                <h1 class="mb-3">Spesial Summer Sale!</h1>
                <p class="mb-4">
                  Spesial offer only on this summer sale get your outfit before
                  it sold.
                </p>
                <a href="#" class="btn btn-danger">Get it Now</a>
              </div>
              <div
                class="col-3 col-sm-6 col-md-4 col-lg-4 d-none d-sm-block offset-1"
              >
                <img class="foto-item" src="img/slideshow/1.jpg" />
              </div>
            </div>
          </div>
          <div class="logo-item">
            <div class="row pt-4 justify-content-center">
              <div class="col-9 col-sm-4 col-md-6 col-lg-4 pt-5 text-left">
                <h1 class="mb-3">Spesial Summer Sale!</h1>
                <p class="mb-4">
                  Spesial offer only on this summer sale get your outfit before
                  it sold.
                </p>
                <a href="#" class="btn btn-danger">Get it Now</a>
              </div>
              <div
                class="col-3 col-sm-6 col-md-4 col-lg-4 d-none d-sm-block offset-1"
              >
                <img class="foto-item" src="img/slideshow/2.jpg" />
              </div>
            </div>
          </div>
        </carousel>
      </div>
    </div>
  </div>
  <!-- Carousel Akhir -->
</template>
<script>
  import carousel from 'vue-owl-carousel';
  export default {
    name: 'CarouselEdiots',
    components: {
      carousel,
    },
  };
</script>

<style scoped>
  .foto-item {
    width: 200px;
    height: 400px;
  }
</style>
