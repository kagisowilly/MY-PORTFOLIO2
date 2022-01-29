<template>
  <!-- projects section -->
  <section
    id="projects"
    class="projects"
    style="background-color: rgb(242 242 252)"
  >
    <div class="container">
      <div class="pb-5 justify-content-center">
        <h1 class="text-center display-6 fw-bold subtitlee"><u>Projects</u></h1>
        <p class="text-center mb-5">Below are some of the projects I've done</p>
        <div class="row col-lg-12 proji" style="row-gap: 30px">
          <div
            v-for="project of projects"
            :key="project.title"
            class="col-lg-3"
            style="display: flex; justify-content: center"
          >
            <div class="card shadow ani-card" style="width: 18rem">
              <img
                :src="project.img"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">{{project.title}}</h4>
                <p class="card-text">{{project.description}}</p>

              <!-- <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">{{project.html}}</li>
                <li class="list-group-item">{{project.css}}</li>
                <li class="list-group-item">{{project.js}}</li>
              </ul> -->

              </div>

              <div class="card-body">
                <a
                  target="_blank"
                  :href="project.netlify"
                  class="card-link"
                  ><button class="project-button">Netlify</button></a>
                <a
                  target="_blank"
                  :href="project.github"
                  class="card-link"
                  ><button>Github</button></a>
              </div>
            </div>
          </div>
          <!-- 
          <div
            class="col-lg-3 "
            style="display: flex; justify-content: center"
          >
            <div class="card shadow ani-card" style="width: 18rem">
              <img
                src="images/projects/Ecom.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">Ecommerce Website</h4>
                <p class="card-text">
                  Ecommerce website built with JS, HTML and CSS.
                </p>
              </div>
              <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">HTML</li>
                <li class="list-group-item">CSS</li>
                <li class="list-group-item">JS</li>
              </ul>
              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayiasics.netlify.app/"
                  class="card-link"
                >
                  <img
                    src="images/projects/netlify_icon_158189.png"
                    class="netlify"
                    alt="Netlify"
                /></a>
                <a
                  target="_blank"
                  href="https://github.com/Kagisomphayi/My-Portfolio"
                  class="card-link"
                  ><img
                    src="images/projects/github.png"
                    class="github"
                    alt="github"
                /></a>
              </div>
            </div>
          </div> -->
          <!-- bhvghjg -->
          <!-- <div class="col-lg-3" style="display: flex; justify-content: center">
            <div class="card shadow ani-card " style="width: 18rem">
              <img
                src="images/projects/bootstrapclone.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">DOOB Website Clone</h4>
                <p class="card-text">Cloning a website</p>
              </div>

              <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">HTML</li>
                <li class="list-group-item">CSS</li>
              </ul>

              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayiclone.netlify.app"
                  class="card-link"
                  ><img
                    src="images/projects/netlify_icon_158189.png"
                    class="netlify"
                    alt="netlify"
                /></a>
                <a
                  target="_blank"
                  href="https://github.com/Kagisomphayi/bootstrap"
                  class="card-link"
                  ><img
                    src="images/projects/github.png"
                    class="github"
                    alt="github"
                /></a>
              </div>
            </div>
          </div>

           -->

          <!-- <div
            class="col-lg-3"
            style="display: flex; justify-content: center"
          >
            <div class="card col shadow ani-card" style="width: 18rem">
              <img
                src="images/projects/calculator.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">Calculator</h4>
                <p class="card-text">Building a functioning calculator</p>
              </div>
              <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">HTML</li>
                <li class="list-group-item">CSS</li>
                <li class="list-group-item">JS</li>
              </ul>
              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayicalculator.netlify.app/"
                  class="card-link"
                >
                  <img
                    src="images/projects/netlify_icon_158189.png"
                    class="netlify"
                    alt="Netlify"
                /></a>
                <a
                  target="_blank"
                  href="https://github.com/Kagisomphayi/Calculator"
                  class="card-link"
                  ><img
                    src="images/projects/github.png"
                    class="github"
                    alt="github"
                /></a>
              </div>
            </div>
          </div>

           <div class="col-lg-3" style="display: flex; justify-content: center">
            <div class="card shadow ani-card " style="width: 18rem">
              <img
                src="images/projects/bootstrapclone.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">DOOB Website Clone</h4>
                <p class="card-text">Cloning a website</p>
              </div>

              <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">HTML</li>
                <li class="list-group-item">CSS</li>
              </ul>

              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayiclone.netlify.app"
                  class="card-link"
                  ><img
                    src="images/projects/netlify_icon_158189.png"
                    class="netlify"
                    alt="netlify"
                /></a>
                <a
                  target="_blank"
                  href="https://github.com/Kagisomphayi/bootstrap"
                  class="card-link"
                  ><img
                    src="images/projects/github.png"
                    class="github"
                    alt="github"
                /></a>
              </div>
            </div>
          </div>

           -->

          <!-- <div
            class="col-lg-3"
            style="display: flex; justify-content: center"
          >
            <div class="card shadow ani-card col " style="width: 18rem">
              <img
                src="images/projects/calculator.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title">Calculator</h4>
                <p class="card-text">Building a functioning calculator</p>
              </div>
              <ul class="list-group px-0 list-group-flush">
                <li class="list-group-item">HTML</li>
                <li class="list-group-item">CSS</li>
                <li class="list-group-item">JS</li>
              </ul>
              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayicalculator.netlify.app/"
                  class="card-link"
                >
                  <img
                    src="images/projects/netlify_icon_158189.png"
                    class="netlify"
                    alt="Netlify"
                /></a>
                <a
                  target="_blank"
                  href="https://github.com/Kagisomphayi/Calculator"
                  class="card-link"
                  ><img
                    src="images/projects/github.png"
                    class="github"
                    alt="github"
                /></a>
              </div>
            </div>
          </div> -->
        </div>
      </div>
    </div>
    <div class="container hr">
      <hr class="" />
    </div>
  </section>
</template>

<script>
export default {
data(){
  return{
        projects: [

          {
        title: "Sonic vs Road Runner",
        github: "https://github.com/Kagisomphayi/Sonic-Roadrun",
        netlify:"https://kagisomphayiroadrunner.netlify.app",
        description: "A race between road runner and sonic.",
        img: "@/assets/sonicproject-min.png",
        // html:"HTML"
      },
      {
        title: "GEL-NIMBUS 23",
        github: "",
        netlify:"",
        description: "",
        img: "https://images.asics.com/is/image/asics/1011B004_404_SR_RT_GLB?$product$",
      },
      {
        title: "Edge II Duffle MD",
        github: "",
        netlify:"",
        description: "",
        img: "https://images.asics.com/is/image/asics/ZR3435_9490_AC_FT_AAC?$sfcc-product$",
      },
      {
        title: "FUJI LITE 2",
        github: "",
        netlify:"",
        description: "",
        img: "https://images.asics.com/is/image/asics/1011B209_400_SR_RT_GLB?$product$",
      },
      {
        title: "JaGEL-KAYANO 28pan",
        github: "",
        netlify:"",
        description:"",
        img: "https://images.asics.com/is/image/asics/1011B189_402_SR_RT_GLB?$zoom$",
      },
      {
        title: "SB TIC POLO",
        github: "",
        netlify:"",
        description:"",
        img: "https://images.asics.com/is/image/asics/2113A060_401_GM_FT_GLB?$zoom$",
      },]
         
  } 
   }


};
</script>

<style></style>
