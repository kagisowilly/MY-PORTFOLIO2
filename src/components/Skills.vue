<template>
  <section id="skills" style="background-color:black">

<h1 class="text-center display-6 subtitlee fw-bold"><u>Skills</u></h1>
        <div id="emailHelp" class="pb-3 form-text text-center">
         <p>My Skills</p> 
        </div>
      
    
    <div class="container col-lg-6">
      <div class="col-lg-10"></div>
      <div class="row justify-content-center">
        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/HTMLL.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/CSS.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/JS.png"
              class="skills img-thumbnail shadow"
              alt="..." shadow
            />
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/vue-logo.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/MYsql.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <img
              src="@/assets/Github.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
          </div>
        </div>
      </div>
    </div>
    <div class="container hr">
      <hr class="bg-white" >
    </div>
  </section>

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
