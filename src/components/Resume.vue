<template>
  <!-- RESUME -->

  <section
    class="education-work"
    id="education"
    style="background-color: black"
  >
    <div class="container mb-5">
      <div class="row justify-content-center" v-if="resumes">
        <div class="col-lg-10 text-white">
          <h1 class="text-center display-6 fw-bold subtitlee mb-5">
            <u>Resume</u>
          </h1>
          <h3 class="text-center pt-5">Education & Experience</h3>
          <ul class="timeline">
            <li v-for="resume of resumes" :key="resume.title">
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-briefcase-fill"></i>{{resume.title}}
                  </h3>
                  <div style="margin-left: 30px">
                    <h6 class="text-muted">{{resume.period}}</h6>
                    <h5>{{resume.institution}}</h5>
                    <p>
                        {{resume.description}}
                    </p>
                  </div>
                </div>
              </div>
            </li>
            
            <br />
          </ul>
        </div>
      </div>
    </div>
    <div class="container hr">
      <hr class="bg-white">
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return { resumes : null,};

  },

      mounted() {
    fetch("https://kagisomphayiportfolio.herokuapp.com/resumes")
      .then((res) => res.json())
      .then(data => {
        console.log(data);
        this.resumes = data;
      });
  },
    };
    
</script>

<style>
ul.timeline {
  list-style-type: none;
  position: relative;
}

ul.timeline:before {
  content: " ";
  background: #d4d9df;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 6;
}
ul.timeline > li {
  margin: 20px 0;
  padding-left: 20px;
}
ul.timeline > li:before {
  content: " ";
  background: rgb(155, 44, 155);
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 10px solid rgb(155, 44, 155);
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 8;
}
.resu {
  width: 90%;
  border-radius: 15px;
}
</style>
