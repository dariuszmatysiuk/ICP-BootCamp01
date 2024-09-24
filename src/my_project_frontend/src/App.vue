<template>
  <div id="app" class="app-container">
    <Header />
    <aboutYou />
    <projects />
    <skils />
    <Contact />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import aboutYou from "./components/aboutYou.vue";
import Contact from "./components/Contact.vue";
import projects from "./components/projects.vue";
import skils from "./components/skils.vue";

export default {
  name: "App",
  components: {
    Header,
    aboutYou,
    Contact,
    projects,
    skils,
  },
};
</script>
