<template>
  <!-- Hero Section Begin -->
  <carousel :items-to-show="4">
    <slide v-for="slide in 5" :key="slide">
      <div class="partner-logo">
        <div class="container">
          <div class="logo-carousel">
            <div class="logo-item">
              <div class="tablecell-inner">
                <img src="img/logo-carousel/logo-1.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
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
  name: "PartnerLascreaCiggaretes",
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
