<template>

<Navbar/>
  <Home />
  <About />
  <Resume />
  <Skills />
  <Projects />
  <Testimonials />
  <Contact />
  <Footer/>


</template>

<script>
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Resume from "./components/Resume.vue";
import Skills from "./components/Skills.vue";
import Projects from "./components/Projects.vue";
import Testimonials from "./components/Testimonials.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Home,
    About,
    Resume,
    Skills,
    Projects,
    Testimonials,
    Contact,
    Footer,
    Navbar,
  },
};
</script>

<style>
.nav-icons{
  font-size: 35px;
}
.footer-icons{
font-size: 20px !important;
color: rgb(155, 44, 155);
}



    .footer-icons:hover{
        color: white;
    }
</style>
