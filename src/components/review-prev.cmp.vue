<template>
  <section class="recommendation">
    <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.</p>
    <avatar-prev :member="member"/>
  </section>
</template>
<script>
import avatarPrev from './avatar-prev.cmp.vue'
export default {
  props: {
    member: Object
  },
  created() {
  console.log(this.member)
  },
  components: {avatarPrev}
}
</script>
<style></style>
