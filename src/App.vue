<template>
  <div>
    <Home />
    <Work />
    <About/>
    <Ablity/>
     <Certificate/>
    <Education/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script setup>
import Work from "./components/Work.vue";
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Ablity from "./components/Ability.vue";
import Education from "./components/Education.vue";
import Certificate from "./components/Certificate.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
