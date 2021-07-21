<template>
  <div>
    <Header />
    <Nameplate />
    <About />
    <Experience />
    <Projects />
    <Contact />
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
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:wght@500&display=swap");

html {
  scroll-behavior: smooth;
}

mark {
  background-color: #faa0a0;
}

@media only screen and (max-width: 768px) {
  #about,
  #experience,
  #projects,
  #contact {
    flex-direction: column;
  }
}
</style>
