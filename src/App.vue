<template>
<Navbar />
<Home/>
  
</template>

<script>
import Navbar from './components/Navbar.vue';
import Home from './components/Home.vue';

export default {
  name: 'App',
  components: {
   Navbar, Home
  }
}
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
  background-image: url("./assets/images/Landing\ Section/background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-image: linear-gradient(
      0deg,
      rgba(0, 0, 0, 0.7),
      rgba(0, 0, 0, 0.7)
    ),
    url(./assets/images/Landing\ Section/background.jpg);
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


</style>
