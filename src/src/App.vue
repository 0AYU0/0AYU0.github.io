<template>
  <div>
    <Header />
    <div class="body">
      <Nameplate />
      <About />
      <Experience />
      <Projects />
      <Contact />
    </div>
  </div>
</template>

<script>
import Nameplate from "./components/Nameplate.vue";
import About from "./components/About.vue";
import Header from "./components/Navigation.vue";
import Experience from "./components/Experience.vue";
import Contact from "./components/Contact.vue";
import Projects from "./components/Projects.vue";

export default {
  name: "App",
  components: {
    About,
    Header,
    Nameplate,
    Experience,
    Contact,
    Projects,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@500&display=swap');
.body {
  margin: 8rem;
}

html {
  scroll-behavior: smooth;
}
</style>
