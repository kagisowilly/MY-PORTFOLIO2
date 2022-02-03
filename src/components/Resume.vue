<template>
  <!-- RESUME -->

  <section
    class="education-work"
    id="education"
    style="background-color: black"
  >
    <div class="container mb-5">
      <div class="row justify-content-center">
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
    return {
      resumes: [
        {
          title: "Web Development",
          period: "September(2016) - Present",
          description: `Life Choices is a year-long Bootcamp where we learn more about Web development and it's Fundamentals. We also get the oppotunity to learn interpersonal skills.`,
          institution: "Life Choices acardemy",
         
        },
        {
          title: "Customer Service",
          description: `We got the opportunity to learn the importanceof strong
                      and consistent communication, dealing with a difficult
                      costomers, how to handle complaints and the value of
                      loyalty in the work industry.`,
          institution: "E-learning colleg",
          icon: "bi bi-mortarboard-fill",
          period: "August(2021)",
        },
        {
          title: "Private Tutoring & Self Learning",
          description: `I was tutoring grade 12 learners Maths and Physics. On my
                      free time i was teaching myself HTML and CSS with the help
                      of online content.`,
          institution: "",

          period: "January 2020 - November 2020",
        },
        {
          title: "Assisting First-Year Students",
          description: `We were assisting first-year Students at the University Of
                      Pretoria with Registering online and using Printing
                      Machines.`,
          institution: "",

          period: "January-february(2018) & January-february(2019)",
        },

        {
          title: "Private Tutoring",
          description: `During this Period i was tutoring some of the grade 12
                      learners from my area Maths and Physics. The experience
                      helped me a lot with improving my communication skills.`,
          institution: "",
          icon: "bi bi-briefcase-fill",
          period: "January 2015 - December 2015",
        },
        {
          title: "National Senior Certificate",
          description: `During my time at this institution i learned to be a leader and i worked more on my time management.`,
          institution: "Mmametlhake High School", 
          period: "January 2012 - December 2014",
        },
      ],
    };
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
