<template>
  <section class="pros-container">
    <div class="pros-wrapper">
      <div v-for="pro in pros" :key="pro.title">
        <div class="flex flex-column align-center pro-preview">
          <img :src="pro.imgUrl" alt="" />
          <h3>{{ pro.title }}</h3>
          <p>{{ pro.content }}</p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import iconAccess from '../assets/svgs/icon-access-anywhere.svg'
import iconSecurity from '../assets/svgs/icon-security.svg'
import iconCollaboration from '../assets/svgs/icon-collaboration.svg'
import iconAnyFile from '../assets/svgs/icon-any-file.svg'

export default {
  data() {
    return {
      pros: [
        {
          title: 'Access your files, anywhere',
          imgUrl: iconAccess,
          content:
            'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.',
        },
        {
          title: 'Security you can trust',
          imgUrl: iconSecurity,
          content:
            '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.',
        },
        {
          title: 'Real-time collaboration',
          imgUrl: iconCollaboration,
          content:
            'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.',
        },
        {
          title: 'Store any type of file',
          imgUrl: iconAnyFile,
          content:
            "Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.",
        },
      ],
    }
  },
}
</script>
<style></style>
