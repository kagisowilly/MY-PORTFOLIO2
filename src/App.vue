<template>
   <!-- NAVBAR -->
        <div>
            <nav class="navbar navbar-expand-md navbar-dark border-muted bg-dark position-fixed w-100 p-0"
                aria-label="Third navbar example" style="z-index: 10;">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#home"><img class="navbar-brand img-responsive"
                            src="@/assets/Logo.png" alt=""></a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarsExample03" aria-controls="navbarsExample03" aria-expanded="false"
                        aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>

                    <div class="collapse navbar-collapse justify-content-end text-end" id="navbarsExample03">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page" href="#home"><i
                                        class="bi bi-house-door"></i><br> Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page" href="#about"><i
                                        class="bi bi-person-lines-fill"></i><br> About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page"
                                    href="#education"><i class="bi bi-card-list"></i><br>
                                    Resume</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page" href="#projects"><i
                                        class="bi bi-briefcase"></i><br>
                                    Projects</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page"
                                    href="#testimonials"><i class="bi bi-person"></i><br> Testimonials</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link active text-muted fw-bold h4" aria-current="page" href="#contact"><i
                                        class="bi bi-chat"></i><br> Contact</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>

        </div>


<Home/>
<About/>
<Resume/>
<Skills/>
<Projects/>
<Testimonials/>
<Contact/>
  
      <!-- Footer -->
    <footer class="page-footer font-small teal pt-2 bg-dark">
        <div class="container text-center text-md-left">
            <div class="d-grid  gap-4 d-flex justify-content-center">
                <a target="_blank" href="https://github.com/Kagisomphayi" class="text-muted  rounded icons "><i
                        class="bi icn bi-github"></i></a>
                <a target="_blank" href="https://www.linkedin.com/in/kagiso-kagiso-5aab71219/"
                    class="text-muted  rounded icons "><i class="bi icn bi-linkedin "></i></a>
                <a target="_blank" href="https://twitter.com/K_Mphayi" class="text-muted  rounded icons"><i
                        class="bi icn bi-twitter  "></i></a>
            </div>
            <div class="container">
                <hr class=" my-1 text-white">
            </div>

            <!-- Copyright -->
            <div class="footer-copyright text-center mb-0 py-1 text-muted h5">©2021 Copyright: Kagiso Mphayi
            </div>
            <!-- Copyright -->
            </div>

    </footer>

  

</template>

<script>

import Home from './components/Home.vue';
import About from './components/About.vue';
import Resume from './components/Resume.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
import Testimonials from './components/Testimonials.vue';
import Contact from './components/Contact.vue';

export default {
  name: 'App',
  components: {
    Home, About, Resume,Skills,Projects,Testimonials,Contact
  }
}
</script>

<style>

</style>
