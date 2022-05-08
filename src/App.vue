<template>
  <div id="app">
    <app-header/>
    <main>
      <app-grid/>
      <app-info/>
    </main>
    <app-footer/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppGrid from './components/AppGrid.vue'
import AppFooter from './components/AppFooter.vue'
import AppInfo from './components/AppInfo.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppGrid,
    AppInfo,
    AppFooter,
    
  }
}
</script>

<style lang="scss">
#app {
  
}
</style>
