<template>
  <div>
    <app-header />
    <router-view />
    <app-footer />
  </div>
</template>
<script>
import appHeader from './components/app-header.vue'
import appFooter from './components/app-footer.vue'

export default {
  name: 'App',
  data() {
    return {}
  },
  components: { appHeader, appFooter },
}
</script>

<style></style>
