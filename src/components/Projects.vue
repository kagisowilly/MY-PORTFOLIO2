<template>
  <!-- projects section -->
  <section
    id="projects"
    class="projects"
    style="background-color: black"
  >
    <div class="container">
      <div class="pb-5 justify-content-center">
        <h1 class="text-center display-6 fw-bold subtitlee"><u>Projects</u></h1>
        <p class="text-center text-muted mb-5">Below are some of the projects I've done</p>
        <div class="row col-lg-12 proji" style="row-gap: 30px">
          <div
            v-for="project of projects"
            :key="project.title"
            class="col-lg-3 col-md-6"
            style="display: flex; justify-content: center"
          >
            <div class="card shadow ani-card" style="width: 18rem">
              <img
                :src="project.img"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h4 class="card-title text-white">{{project.title}}</h4>
                <p class="card-text text-white">{{project.description}}</p>

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
                  ><button class="btn btn-warning mt-0 rounded-pill">Netlify</button></a>
                <a
                  target="_blank"
                  :href="project.github"
                  class="card-link "
                  ><button class="btn btn-warning mt-0 rounded-pill">Github</button></a>
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
                <li class="list-group-item">CSS</li>proj
                <li class="list-group-item">JS</li>
              </ul>
              <div class="card-body">
                <a
                  target="_blank"
                  href="https://kagisomphayiasics.netlify.app/"
                  class="card-link"
                >
                  <imgproj
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
                    alt="github"https://github.com/Kagisomphayi/My-Portfolio
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
      <hr class="bg-white" >
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
        description: "A race between road runner and sonic.(CSS & HTML)",
        img: "https://i.postimg.cc/RZcd1JZZ/sonicproject-min.png",
        // html:"HTML"
      },
      {
        title: "Ecommerce Website",
        github: "https://github.com/Kagisomphayi/ASICSSTORE",
        netlify:"https://kagisomphayiasics.netlify.app/",
        description: "Ecommerce website built with JS, HTML and CSS.",
        img: "https://i.postimg.cc/ydwnXmcW/Ecom.png",
      },
      {
        title: "Cloning a website",
        github: "https://github.com/Kagisomphayi/bootstrap",
        netlify:"https://kagisomphayiclone.netlify.app",
        description: "Cloning DOOB Website using Bootstrap,CSS & HTML.",
        img: "https://i.postimg.cc/Bn9zT044/bootstrapclone.png",
      },
      {
        title: "Javascript Calculator",
        github: "https://github.com/Kagisomphayi/Calculator",
        netlify:"https://kagisomphayicalculator.netlify.app/",
        description: "Building a functioning calculator(HTML,CSS & JS",
        img: "https://i.postimg.cc/1Xx9wdzT/calculator.png",
      },
      
      
]
         
  } 
   }


};
</script>

<style>

</style>
