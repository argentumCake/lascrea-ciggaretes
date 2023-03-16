<template>
  <div class="home">
    <header-lascrea-ciggaretes />
    <hero-lascrea-ciggaretes />
    <women-lascrea-ciggaretes />
    <insta-lascrea-ciggaretes />
    <partner-lascrea-ciggaretes />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderLascreaCiggaretes from "@/components/HeaderLascreaCiggaretes.vue";
import HeroLascreaCiggaretes from "@/components/HeroLascreaCiggaretes.vue";
import WomenLascreaCiggaretes from "@/components/WomenLascreaCiggaretes.vue";
import InstaLascreaCiggaretes from "@/components/InstaLascreaCiggaretes.vue";
import PartnerLascreaCiggaretes from "@/components/PartnerLascreaCiggaretes.vue";

export default {
  name: "HomeView",
  components: {
    HeaderLascreaCiggaretes,
    HeroLascreaCiggaretes,
    WomenLascreaCiggaretes,
    InstaLascreaCiggaretes,
    PartnerLascreaCiggaretes,
  },
};
</script>
