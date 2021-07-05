<template>
  <v-app>
    <app-navigation/>
    <v-content transition="slide-x-transition">
      <route-view>

      </route-view>
    </v-content>
  </v-app>
</template>

<script>
import AppNavigation from './components/AppNavigation.vue'
export default {
  components: { AppNavigation },
}
</script>

<style>

</style>