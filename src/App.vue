<<<<<<< HEAD
<template >
=======
<template>
>>>>>>> cc298a4acf18de84e3d920d5d6aaf899868fa027
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
<<<<<<< HEAD
  max-width: 98%;
=======
>>>>>>> cc298a4acf18de84e3d920d5d6aaf899868fa027
}
</style>
