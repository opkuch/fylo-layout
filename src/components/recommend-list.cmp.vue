<template>
  <section class="">
    <div class="recommend-list">
        <recommend-prev v-for="member in members" :key="member.fullname" :member="member" />
        <img class="quotes-img" src="../assets/images/bg-quotes.png" />
    </div>
  </section>
</template>
<script>
import recommendPrev from './recommend-prev.cmp.vue'
export default {
  data() {
    return {
      members: [
        {
          fullname: 'Satish Patel',
          job: 'Founder & CEO, Huddle',
          imgUrl: './src/assets/images/profile-1.jpg',
        },
        {
          fullname: 'Bruce McKenzie',
          job: 'Founder & CEO, Huddle',
          imgUrl: './src/assets/images/profile-2.jpg',
        },
        {
          fullname: 'Satish Patel',
          job: 'Founder & CEO, Huddle',
          imgUrl: './src/assets/images/profile-3.jpg',
        },
      ],
    }
  },
  components: { recommendPrev },
}
</script>
<style></style>
