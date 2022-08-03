<template>
  <section class="wide-layout homepage-container">
    <hero-cmp />
    <pros />
    <bottom-hero />
    <recommend-list />
    <early-access />
  </section>
</template>
<script>
import heroCmp from '../components/hero.cmp.vue'
import bottomHero from '../components/bottom-hero.vue'
import pros from '../components/pros.vue'
import RecommendList from '../components/recommend-list.cmp.vue'
import earlyAccess from '../components/early-access.vue'
export default {
  components: { heroCmp, pros, bottomHero, RecommendList, earlyAccess },
}
</script>
<style></style>
