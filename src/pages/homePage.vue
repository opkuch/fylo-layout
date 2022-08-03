<template>
  <section class="wide-layout homepage-container">
    <hero-cmp />
    <pros />
    <bottom-hero />
    <review-list />
    <early-access />
  </section>
</template>
<script>
import heroCmp from '../components/hero.cmp.vue'
import bottomHero from '../components/bottom-hero.vue'
import pros from '../components/pros.vue'
import reviewList from '../components/review-list.vue'
import earlyAccess from '../components/early-access.vue'
export default {
  components: { heroCmp, pros, bottomHero, reviewList, earlyAccess },
}
</script>
<style></style>
