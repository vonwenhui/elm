<template>
  <div id="app">
    <elm-header></elm-header>
    <elm-nav></elm-nav>
    <router-view/>
  </div>
</template>

<script>
import ElmHeader from '@/components/ElmHeader'
import ElmNav from '@/components/ElmNav'
export default {
  name: 'App',
  components: {
    ElmHeader,
    ElmNav
  }
}
</script>

<style scoped>
</style>
