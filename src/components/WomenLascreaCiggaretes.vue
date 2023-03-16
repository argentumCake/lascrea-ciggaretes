<template>
  <!-- Hero Section Begin -->
  <carousel :items-to-show="4">
    <slide v-for="slide in 5" :key="slide">
      <section class="women-banner spad">
        <div class="container-fluid">
          <div class="row">
            <div class="col-lg-12 mt-5">
              <div class="product-slider set-bg">
                <div class="product-item">
                  <div class="pi-pic">
                    <img src="img/mickey1.jpg" alt="" />
                    <ul>
                      <li class="w-icon active">
                        <a href="#"><i class="icon_bag_alt"></i></a>
                      </li>
                      <li class="quick-view">
                        <a href="product.html">+ Quick View</a>
                      </li>
                    </ul>
                  </div>
                  <div class="pi-text">
                    <div class="catagory-name">Coat</div>
                    <a href="#">
                      <h5>Mickey Baggy</h5>
                    </a>
                    <div class="product-price">
                      $14.00
                      <span>$35.00</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </slide>
    <template #addons>
      <navigation />
    </template>
  </carousel>
  <!-- Hero Section End -->
</template>

<script>
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Navigation } from "vue3-carousel";

export default {
  name: "WomenLascreaCiggaretes",
  components: {
    Carousel,
    Slide,
    Navigation,
  },
};
</script>

<style scoped>
.set-bg {
  width: 200px;
  height: 400px;
}

.banner-info {
  margin-top: 130px;
}
</style>
