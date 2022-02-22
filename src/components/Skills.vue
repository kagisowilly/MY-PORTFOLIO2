<template>
  <section id="skills" style="background-color: black">
    <h1 class="text-center display-6 subtitlee fw-bold"><u>Skills</u></h1>
    <div id="emailHelp" class="pb-3 form-text text-center">
      <p>Hover Over the images to see my ratings</p>
    </div>

    <div class="container col-lg-6 mt-5">
      <div class="col-lg-10"></div>
      <div class="row justify-content-center">
        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">
            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
                  <img
                    src="@/assets/HTMLL.png"
                    class="skills img-thumbnail shadow"
                    alt="..."
                  />
                </div>
                <div class="flip-card-back">
                  <p id="flip-back">75-90%</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">

            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
            <img
              src="@/assets/CSS.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
                </div>
                <div class="flip-card-back">
                  <p id="flip-back">70-90%</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">


            <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/JS.png"
              class="skills img-thumbnail shadow"
              alt="..."
              shadow
            />
    </div>
    <div class="flip-card-back">
      <p id="flip-back">50-75%</p>
    </div>
  </div>
</div>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">

            <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/vue-logo.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
    </div>
    <div class="flip-card-back">
      <p id="flip-back">75 - 100%</p>
    </div>
  </div>
</div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">

            <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/MYsql.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
    </div>
    <div class="flip-card-back">
      <p id="flip-back">75-100%</p>
    </div>
  </div>
</div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">

            <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/Bootstrap.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
    </div>
    <div class="flip-card-back">
      <p id="flip-back">70-100%</p>
    </div>
  </div>
</div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">


          <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/node.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
    </div>
    <div class="flip-card-back">
      <p id="flip-back">50-75%</p>
    </div>
  </div>
</div>
          </div>
        </div>

        <div class="col-4 col-xs-4 col-sm-4 col-md-4">
          <div class="box">

            <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
            <img
              src="@/assets/Github.png"
              class="skills img-thumbnail shadow"
              alt="..."
            />
    </div>
    <div class="flip-card-back">

      <p id="flip-back">75-100%</p>
    </div>
  </div>
</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
/* SKILLS */
.box {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  min-height: 180px;
}

.skills {
  border-radius: 50%;
  height: auto;
  margin: auto;
  width: 150px;
}

.flip-card {
  background-color: transparent;
  width: 300px;
  height: 180px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: none;
  color: black;
}

.flip-card-back {
  background-color:none;
  color: white;
  transform: rotateY(180deg);
  border-radius: 100%;
}

#flip-back{
  margin-top: 23%;
  font-weight: bold;
  color:rgb(209, 82, 209);
  font-size: 25px;
  
}
</style>
