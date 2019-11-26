<template>
  <div class="index-page"><app-component></app-component></div>
</template>

<script>
import AppComponent from '../components/component'

export default {
  name: 'Page',
  components: {
    AppComponent,
  },
  head: {
    title: 'fresh',
  },
}
</script>

<style scoped>
.index-page {
  width: 100%;
  display: block;
  overflow: auto;
  font-size: 16px;
  min-height: 100vh;
  font-family: Open Sans;
  background-color: #fff;
}
</style>
