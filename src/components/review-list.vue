<template>
  <section class="">
    <div class="recommend-list">
        <review-prev v-for="member in members" :key="member.fullname" :member="member" />
        <img class="quotes-img" src="../assets/images/bg-quotes.png" />
    </div>
  </section>
</template>
<script>
import reviewPrev from './review-prev.cmp.vue'
import profile1 from '../assets/images/profile-1.jpg'
import profile2 from '../assets/images/profile-2.jpg'
import profile3 from '../assets/images/profile-3.jpg'

export default {
  data() {
    return {
      members: [
        {
          fullname: 'Satish Patel',
          job: 'Founder & CEO, Huddle',
          imgUrl: profile1,
        },
        {
          fullname: 'Bruce McKenzie',
          job: 'Founder & CEO, Huddle',
          imgUrl: profile2,
        },
        {
          fullname: 'Satish Patel',
          job: 'Founder & CEO, Huddle',
          imgUrl: profile3,
        },
      ],
    }
  },
  components: { reviewPrev },
}
</script>
<style></style>
