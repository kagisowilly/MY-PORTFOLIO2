<template>
  <section id="skills">

<h1 class="text-center display-6 subtitlee fw-bold mb-5"><u>Skills</u></h1>
      
    
    <div class="container col-lg-12">
      <div class="col-lg-10"></div>
      <div class="row justify-content-center">
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/HTMLL.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/CSS.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/JS.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/vue-logo.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/MYsql.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="box">
            <img
              src="@/assets/Github.png"
              class="skills img-thumbnail"
              alt="..."
            />
          </div>
        </div>
      </div>
    </div>
  </section>
  <div class="container hr">
    <hr class="bg-dark" />
  </div>
</template>

<script>
export default {};
</script>

<style>
/* SKILLS */
.box {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0;
  padding: 10px;
  width: 100%;
  min-height: 200px;
}

      .skills {
        border-radius: 50%;
        height: auto;
        margin: auto;
        width: 150px;
      }
</style>
