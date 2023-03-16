<template>
  <!-- Hero Section Begin -->
  <carousel :items-to-show="5">
    <slide v-for="slide in 5" :key="slide">
      <div class="instagram-photo">
        <div
          class="insta-item set-bg"
          style="background-image: url('/img/insta-1.jpg')"
        >
          <div class="inside-text">
            <i class="ti-instagram"></i>
            <h5><a href="#">shayna_gallery</a></h5>
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
  name: "InstaLascreaCiggaretes",
  components: {
    Carousel,
    Slide,
    Navigation,
  },
};
</script>

<style scoped>
.set-bg {
  width: 250px;
  height: 200px;
}

.banner-info {
  margin-top: 130px;
}
</style>
