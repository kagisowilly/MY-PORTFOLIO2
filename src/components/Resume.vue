<template>
  <!-- RESUME -->

  <section
    class="education-work"
    id="education"
    style="background-color: rgb(242 242 252)"
  >
    <div class="container mb-5">
      <div class="row justify-content-center">
        <div class="col-lg-10">
          <h1 class="text-center display-6 fw-bold subtitlee mb-5">
            <u>Resume</u>
          </h1>
          <h3 class="text-center pt-5">Education & Experience</h3>
          <ul class="timeline">
            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-mortarboard-fill"></i>  Web Development
                  </h3>
                  <div style="margin-left: 30px">
                    <h6 class="text-muted">September(2016) - Present</h6>
                    <h5>Life Choices acardemy</h5>
                    <p>
                      Life Choices is a year-long Bootcamp where we learn more
                      about Web development and it's Fundamentals. We also get
                      the oppotunity to learn interpersonal skills.
                    </p>
                  </div>
                </div>
              </div>
            </li>
            <br />
            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-mortarboard-fill"></i> Customer Service
                  </h3>
                  <div style="margin-left: 30px">
                    <h6 class="text-muted">August(2021)</h6>
                    <h5>E-learning college</h5>
                    <p>
                      We got the opportunity to learn the importanceof strong
                      and consistent communication, dealing with a difficult
                      costomers, how to handle complaints and the value of
                      loyalty in the work industry.
                    </p>
                  </div>
                </div>
              </div>
            </li>
            <br />
            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-briefcase-fill"></i> Private Tutoring & Self Learning
                  </h3>

                  <div style="margin-left: 30px">
                    <h6 class="text-muted">January 2020 - November 2020</h6>

                    <p>
                      I was tutoring grade 12 learners Maths and Physics. On my
                      free time i was teaching myself HTML and CSS with the help
                      of online content.
                    </p>
                  </div>
                </div>
              </div>
            </li>
            <br />
            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-briefcase-fill"></i> Assisting First-Year
                    Students
                  </h3>

                  <div style="margin-left: 30px">
                    <h6 class="text-muted">
                      January-february(2018) & January-february(2019)
                    </h6>

                    <p>
                      We were assisting first-year Students at the University Of
                      Pretoria with Registering online and using Printing
                      Machines.
                    </p>
                  </div>
                </div>
              </div>
            </li>
            <br />

            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3><i class="bi bi-briefcase-fill"></i> Private Tutoring</h3>

                  <div style="margin-left: 30px">
                    <h6 class="text-muted">January 2015 - December 2015</h6>
                    <p>
                      During this Period i was tutoring some of the grade 12
                      learners from my area Maths and Physics. The experience
                      helped me a lot with improving my communication skills.
                    </p>
                  </div>
                </div>
              </div>
            </li>

            <br />
            <li>
              <div class="resu shadow">
                <div class="p-2">
                  <h3>
                    <i class="bi bi-mortarboard-fill"></i> National Senior
                    Certificate
                  </h3>
                  <div style="margin-left: 30px">
                    <h6 class="text-muted">January 2012 - December 2014</h6>
                    <h5>Mmametlhake High School</h5>
                  </div>

                  <p></p>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="container hr">
      <hr class="" />
    </div>
  </section>
</template>

<script>
export default {};
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
  background: rgb(223, 146, 4);
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid rgb(223, 146, 4);
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 8;
}
.resu {
  width: 90%;
  ;
  border-radius: 15px;
}
</style>
