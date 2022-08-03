<template>
<div class="flex align-center">
    <img :src="member.imgUrl" style="max-width: 32px; max-height: 32px; border-radius: 50%;">
    <div class="member-details">
        <h3>{{member.fullname}}</h3>
        <span>{{member.job}}</span>
    </div>
</div>
</template>
<script>
export default {
    name: 'avatar-prev',
    props: {
        member: Object,
    },
    created () {
        console.log(this.member)
    }
}
</script>