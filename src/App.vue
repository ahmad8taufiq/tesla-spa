<template>
  <v-app>
    <app-navigation/>
    <promo />
    <v-content transition="slide-x-transition">
      <route-view></route-view>
    </v-content>
  </v-app>
</template>

<script>
import AppNavigation from './components/AppNavigation.vue'
// import Promo from './components/Promo.vue'
// import Home from './views/Home.vue'
export default {
  components: { AppNavigation },
}
</script>

<style>

</style>