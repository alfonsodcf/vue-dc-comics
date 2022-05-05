<template>
  <div id="app">
    <app-header/>
    <main>
      <app-grid/>
    </main>
    <app-footer/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppGrid from './components/AppGrid.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppGrid,
    AppFooter,
  }
}
</script>

<style lang="scss">
#app {
  
}
</style>
