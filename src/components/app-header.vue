<template>
    <header class="wide-layout app-header-container ">
      <div class="flex justify-between align-center">
        <app-logo />
        <main-navbar />
      </div>
    </header>
</template>
<script>
import appLogo from './app-logo.cmp.vue'
import mainNavbar from './main-navbar.cmp.vue'
export default {
  components: { mainNavbar, appLogo },
    
}
</script>
<style>
    
</style>