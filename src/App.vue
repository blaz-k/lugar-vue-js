<template>
  <Navbar />
  <Hero />
  <About />
  <Projects />
  <Testimonial />
  <Contact />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import About from "./components/About.vue";
import Projects from "./components/Projects.vue";
import Testimonial from "./components/Testimonial.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Hero,
    About,
    Projects,
    Testimonial,
    Contact,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
