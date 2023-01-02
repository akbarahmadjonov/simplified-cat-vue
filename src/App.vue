<template>
  <div id="app">
    <Nav />
    <About />
    <Test />
    <Footer />
  </div>
</template>

<script>
import Nav from "./components/nav.vue";
import About from "./components/aboutCats.vue";
import Test from "./components/testimonial.vue";
import Footer from './components/footer.vue'

export default {
  name: "App",
  components: {
    Nav,
    About,
    Test,
    Footer
  }
}
</script>

<style></style>
