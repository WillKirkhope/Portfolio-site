<template lang="html">
<div class="home">
<div class="about">
  <About />
  </div>
  <div class="skills">
    <Skills />
  </div>
  <div class="projects">
    <Projects />
  </div>
  <div class="contact">
    <Contact />
  </div>
  </div>
</template>

<script>
import About from './About'
import Skills from './Skills'
import Projects from './Projects'
import Contact from './Contact'

export default {
  name: 'Home',
  components: {
    About,
    Skills,
    Projects,
    Contact
  }
}
</script>

<style lang="css">


</style>
