<script>
import Navbar from "../components/Navbar.vue";
import HeroSection from "../components/HeroSection.vue";
import About from "../components/About.vue";
import Project from "../components/Projects.vue";
export default {
  components: {
    Navbar,
    HeroSection,
    About,
    Project,
  },
};
</script>

<template>
  <div class="d-flex flex-column">
    <div>
      <Navbar />
    </div>
    <div>
      <HeroSection />
    </div>
    <div>
      <About />
    </div>
    <div>
      <Project />
    </div>
  </div>
</template>

<style scoped></style>
