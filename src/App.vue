<template>
  <div id="app">
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import Content from './components/Content.vue'
import Footer from "./components/Footer.vue";

export default {
  name: 'app',
  components: {
    Content,
    Footer
  }
}
</script>

<style>

</style>
