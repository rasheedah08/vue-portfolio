<template>
  <navbar />
  <!-- <HomeView /> -->
  <!-- <about-view />
  <Resume />
  <Testimonials />
  <Education />
  <Projects />
  <Contact /> -->
  <!-- <v-app> -->
  <v-main>
    <router-view/>
  </v-main>
  <footer />
</template>

<script>
import navbar from "./components/Navbar.vue";
import footer from "./components/Footer.vue";
import AboutView from "./views/AboutView.vue";
import Contact from "./views/Contact.vue";
import Resume from "./views/Resume.vue";
import Testimonials from "./views/Testimonials.vue";
import Projects from "./views/Projects.vue";
import Footer from "./components/Footer.vue";
import HomeView from "./views/HomeView.vue";
import Education from "./views/Education.vue";
export default {
  // name: 'App',
  components: {
    navbar,
    footer,
    AboutView,
    Contact,
    Resume,
    Testimonials,
    Projects,
    Footer,
    HomeView,
    Education
},
};
</script>

<style>
#app {
  background-color: #337595;
}
</style>
