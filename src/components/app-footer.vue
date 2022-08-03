<template>
  <footer>
    <div class="footer-wrapper flex flex-column justify-center">
      <app-logo />
      <div class="flex footer-content">
        <section class="footer-layout company-location">
          <img class="footer-icon" src="../assets/svgs/icon-location.svg" />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua
          </p>
        </section>
        <section class="footer-layout contact-us">
          <img class="footer-icon" src="../assets/svgs/icon-phone.svg" />
          <span>+1-543-123-4567</span>
          <img class="footer-icon" src="../assets/svgs/icon-email.svg" />
          <span>example@fylo.com</span>
        </section>
        <section class="app-links">
          <ul class="clean-list">
            <li>About Us</li>
            <li>Contact Us</li>
            <li>Jobs</li>
            <li>Terms</li>
            <li>Press</li>
            <li>Privacy</li>
            <li>Blog</li>
          </ul>
        </section>
        <section class="social-links flex">
          <img src="../assets/svgs/logo-facebook.svg" />
          <img src="../assets/svgs/logo-instagram.svg" />
          <img src="../assets/svgs/logo-twitter.svg" />
        </section>
      </div>
    </div>
  </footer>
</template>
<script>
import appLogo from './app-logo.cmp.vue'

export default {
  components: { appLogo },
}
</script>
<style></style>
