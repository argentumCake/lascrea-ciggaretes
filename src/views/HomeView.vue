<template>
  <div class="home">
    <header-lascrea-ciggaretes />
    <hero-lascrea-ciggaretes />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderLascreaCiggaretes from '@/components/HeaderLascreaCiggaretes.vue'
import HeroLascreaCiggaretes from '@/components/HeroLascreaCiggaretes.vue'


export default {
  name: 'HomeView',
  components: {
    HeaderLascreaCiggaretes,
    HeroLascreaCiggaretes,
  }
}
</script>
