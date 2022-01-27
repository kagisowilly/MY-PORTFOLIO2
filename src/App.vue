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
<Skills/>
  
</template>

<script>

import Home from './components/Home.vue';

import About from './components/About.vue';
import Skills from './components/Skills.vue';

export default {
  name: 'App',
  components: {
    Home, About,Skills
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */


/* Navbar Section*/

.nav-link {
  text-align: center;
}
.nav-link:hover {
  color: rgb(255, 176, 6) !important;
}

.github:hover {
  background-color: rgb(255, 176, 6) !important;
  border-radius: 50%;
}

.netlify:hover {
  background-color: rgb(255, 176, 6) !important;
  border-radius: 50%;
}
.navbar {
  top: 0;
}

.navbar-brand {
  border-radius: 100%;
  height: 100px;
  width: 60x;
  padding-bottom: 4px !important;
  padding-top: 3px !important;
  margin-top: 0px !important;
  margin-bottom: 3px !important;
}

.one {
  display: grid;
  margin-top: 20px;
  padding-top: 100px;
  overflow-x: hidden !important;
}

 .num-one {
  height: 100vh;
  margin-top: 0;
  background-image: url("./assets/background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-image: linear-gradient(
      0deg,
      rgba(0, 0, 0, 0.7),
      rgba(0, 0, 0, 0.7)
    ),
    url(./assets/background.jpg);
  overflow-x: hidden;
  background-position: center;
}


  /* BACKGROUND COLOR */
  hr {
    margin-top: 0px;
    margin-bottom: 0px;
  }
  /* icons */
  .icons {
    height: 40px;
    width: 40px;
    line-height: 2;
    border-radius: 100% !important;
  }
  
  /* form {
    width: 40% !important;
  } */
  .contactMe {
    width: 100%;
    margin: 0px;
  }
  .icons:hover {
    color: rgb(255, 176, 6) !important;
  }
  
  .button-about {
    width: 25%;
  }
  
  .arrow {
    height: 40px;
    width: 40px;
  }


  .subtitlee {
    padding-top: 100px;
  }
  
  .image-col {
    height: 300px;
    width: 300px;
    border-radius: 50%;
  }
  
  .profile2 {
    height: auto;
    width: 200px;
    border-radius: 100%;
    float: left;
  }
  
.p-bar,
  .p-inner {
    border-radius: 15px;
  }
  
  .p-inner {
    border-radius: 15px;
    background-color: orange;
  }
 /* SKILLS */
.box {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #aaa;
  margin: 20px 0;
  padding: 10px;
  width: 100%;
  min-height: 200px;
  border: 2px #ccc solid;
  color: #fff;
}

</style>
