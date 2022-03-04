<template>
  <!-- projects section -->
  <section id="projects" class="projects" style="background-color: black">
    <div class="container hr">
      <hr class="bg-white" />
    </div>
    <div class="container">
      <div class="pb-5 justify-content-center">
        <h1 class="text-center display-6 fw-bold subtitlee"><u>Projects</u></h1>
        <p class="text-center text-muted mb-5 ">
          Below are some of the projects I've done
        </p>
        <div class="row col-lg-12 proji" style="row-gap: 30px">
          <div
            v-for="project of projects"
            :key="project.title"
            class="col-lg-3  col-md-6"
            style="display: flex; justify-content: center"
          >

            <div class="card ani-card card-shadow" style="width: 18rem">
              <img :src="project.img" class="card-img-top" alt="..." />
              <div class="card-body">
                <h4 class="card-title text-white">{{ project.title }}</h4>
                <p class="card-text text-white">{{ project.description }}</p>
              </div>

              <div class="card-body card-icons">
                <a target="_blank" :href="project.netlify" class="card-link"
                  ><button class=" mt-0 rounded">
                   <img class="icon" src="@/assets/netlify.png" alt="Netlify">
                  </button></a
                >
                <a target="_blank" :href="project.github" class="card-link"
                  ><button class=" mt-0 rounded">
                    <img class="icon" src="@/assets/githubicon.png" alt="Github">
                  </button></a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container hr">
      <hr class="bg-white" />
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: null,
    };
  },
  mounted() {
    fetch("https://kagisomphayiportfolio.herokuapp.com/projects")
      .then((res) => res.json())
      .then((data) => {
        console.log(data);
        this.projects = data;
      });
  },
};
</script>

<style scoped>
.card-shadow{
-webkit-box-shadow: -12px 11px 12px 2px rgba(95,0,170,0.3); 
box-shadow:  -12px 11px 12px 2px rgba(95,0,170,0.3);
      border: none;
}
button{
  background-color: transparent;
  border: none;
}
.card-icons{
  justify-content: center;
  display: flex;
  flex-wrap: wrap;
}

.icon:hover{
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.5); 
}
</style>
