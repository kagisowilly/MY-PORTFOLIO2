<template>
  <section

  
    class="about-section"
    id="about"
    style="background-color: black"
  >

    <div class="container pb-3" style="background-color: black">
      <h1 class="text-center display-6 subtitlee fw-bold mb-5"><u>About</u></h1>
                <div class="text-center "><h3  class="text-white intro">Introduction</h3></div>
      <div class="row justify-content-center text-white">
        <div class="col col-lg-10 abountcont col-md-10">
          <img
            src="@/assets/profile-min.jpg"
            alt="profile"
            class="img-responsive profile2"
          />

          
          <p>
            I am a hard-working individual who never shies away from a
            challenge. I am always willing to help the person next to me.
            Furthermore, I am a good communicator, and this is one of the
            reasons why I work well with people. I am always eager to expand my
            knowledge, and I am a fast learner as well.
          </p>
          <p class="mt-3">
            My passion for the tech industry started from having conversations
            with some of my close friends who are already in the field of
            technology. As someone who is always eager to learn new things and
            who's obsessed with improving the world we live in, my passion
            developed more.
          </p>
        </div>
      </div>

      <div class="row justify-content-center pt-3">
        <div class="col-lg-6 col-md-5">
          <table class="table  text-white table-bordered">
            <thead>
              <tr>
                <th scope="col">Personal Details</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><b class="text-muted">Full name:</b> Kagiso Mphayi</td>
              </tr>
              <tr>
                <td><b class="text-muted">Date of birth:</b> 01/07/1996</td>
              </tr>
              <tr>
                <td><b class="text-muted">Location:</b> Cape Town,South Africa</td>
              </tr>
              <tr>
                <td><b class="text-muted">Cell Phone number:</b> 079 928 2407</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="col col-lg-6 col-md-5">
          <table class="table  text-white table-bordered">
            <thead>
              <tr class="text-white">
                <th scope="col text-muted">Passion Board</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Reading</td>
              </tr>
              <tr>
                <td>Chess</td>
              </tr>
              <tr>
                <td>Mind-Challenging Games</td>
              </tr>
              <tr>
                <td>Soccer</td>
              </tr>
            </tbody>
          </table>
        </div>

        <div class="col col-lg-10 col-md-10">
          <table class="table  text-white table-bordered">
            <thead>
              <tr>
                <th scope="col">Soft Skills</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Communication & Leadership</td>
              </tr>
              <tr>
                <td>Time Management</td>
              </tr>
              <tr>
                <td>Problem-Solving</td>
              </tr>
              <tr>
                <td>Flexibility/Adaptability</td>
              </tr>
            </tbody>
          </table>
        </div>

      </div>
    </div>

            <div class="container hr">
            <hr class=" bg-white">
        </div>
  </section>
</template>

<script>
export default {};
</script>

<style>

table.table-bordered > thead > tr > th{
    border:1px solid rgb(116, 116, 116);
}
table.table-bordered > tbody > tr > td{
    border:1px solid rgb(116, 116, 116);
}

td,tr{
  font-size: large;
}
th{
  font-size: larger;
}

</style>
