<script setup>
  import Navbar from './components/Navbar.vue'
  import Header from './components/Header.vue'
  import About from './components/About.vue'
  import Projects from './components/Projects.vue'
  import Client from './components/Client.vue'
  import Experiences from './components/Experiences.vue'
  import Contact from './components/Contact.vue'
  import Footer from './components/Footer.vue'

</script>

<template>
  <div class="p-10 px-20 flex flex-col gap-5">
    <Navbar />
    <Header />
    <About />
    <Experiences />
    <Projects />
    <Client />
    <Contact />
    <Footer />
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>


