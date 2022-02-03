<template>
  <!-- Testimonials -->
  <section
    class="testimonial-background"
    style="background-color: black"
    id="testimonials"
  >

        <div class="container">
            <h1 class="text-center display-6 mb-5  fw-bold subtitlee"><u>Testimonials</u> </h1>
            <div id="carouselExampleControlsNoTouching" class="carousel testi slide text-black col-lg-10"
                data-bs-touch="false" data-bs-interval="false">

                <div class="row text-center ">
                    <div class="carousel-inner pb-5 text-white">
                        <div class="carousel-item pt-3">
                            <img src="@/assets/Aza-min.jpg" class="d-block img-thumbnail" alt="...">
                            <div class="">
                                <p class="h5 names text-center">Azabenathi Pupuma</p>
                                <b class="roles">Web Developer</b>

                                <p class="text-center mt-3">Kagiso is one of the hard workers you could come across.
                                    <br> He
                                    always
                                    ensure
                                    that he gets the hang of his work and he does not stop until he finishes. He is goal
                                    oriented.</p>
                            </div>
                        </div>
                        <div class="carousel-item pt-3">
                            <img src="@/assets/Godwin.jpeg" class="d-block img-thumbnail" alt="...">
                            <div class="">
                                <p class="h5 names text-center">Godwin Dzvapatsva</p>
                                <b class="roles">Head of Curriculum and Learning @ 'lifechoices coding
                                    acardemy'</b>
                                <p class="text-center mt-3">Kagiso is a diligent student who thrives to do the best and
                                    is
                                    always
                                    time concious. <br> I
                                    recommend him.
                                </p>
                            </div>

                        </div>
                        <div class="carousel-item pt-3">
                            <img src="@/assets/nomv-min.jpg" class="d-block img-thumbnail" alt="...">
                            <div>
                                <p class="h5 names text-center">Nomzuyiseko Mpofu</p>
                                <b class="roles">Web Developer</b>
                                <p class="text-center mt-3">Kagiso is a person of humble character, <br> easy to work
                                    with
                                    and so
                                    far
                                    he shown dedication and great work ethic.I admire his time management.</p>
                            </div>

                        </div>
                        <div class="carousel-item active pt-3">
                            <img src="@/assets/Lilitha-min.jpg" class="d-block img-thumbnail" alt="...">
                            <div class="">
                                <p class="h5 names text-center">Lilitha Mantini</p>
                                <b class=" roles">Web Developer</b>
                                <p class="text-center mt-3">I have worked closely on a group with Kagiso. He's a team
                                    player
                                    with
                                    good communication skills, <br> not afraid of challenges and always willing to
                                    assist
                                    where
                                    he can.</p>
                            </div>
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button"
                        data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon " aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button"
                        data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>


    <div class="container hr">
      <hr class="bg-white" >
    </div>
        </div>

  </section>
</template>

<script>
export default {
//   data() {
//     return {
//       testimonials: [
//         {
//           name: "Azabenathi Pupu",
//           image: "",
//           role: `Web Developer`,
//           description: `Kagiso is one of the hard workers you could come across.
//                         He always ensure that he gets the hang of his work and he does not 
//                          stop until he finishes. He is goal oriented.`,
//         },
//         {
//           name: "Godwin Dzvapatsva",
//           image: ``,
//           role: `Head Of Curriculum And Learning @ Lifechoices Coding
//                                     Acardemy`,
//           description: `Kagiso is a diligent student who thrives to do the best and
//                                     is
//                                     always
//                                     time concious.I
//                                     recommend him.`,
//         },
//         {
//           name: "Nomzuyiseko Mpofu",
//           image: ``,
//           role: " Web designer",

//           description: `Kagiso is a person of humble character easy to work with and so far
//                          he shown dedication and great work ethic.I admire his time management.`,
//         },
//         {
//           name: "Lilitha Mantini",
//           image: ``,
//           role: "Web Develope",

//           description: `Kagiso is one of the hard workers you could come across. 
//           He always ensure that he gets the hang of his work and he does not
//            stop until he finishes. He is goal oriented.`,
//         },


//       ],
//     };
//   },
};
</script>

<style>
.d-block {
  border-radius: 50%;
  height: 200px;
  margin: auto;
  width: 200px;
}
.carousel-item {
  /* background-color: #d4d9df; */
  border-radius: 15px;
  height: 450px;
}

.carousel-control-prev-icon {
  background-color: rgb(155, 44, 155);
  margin-bottom: 230px;
}

.carousel-control-prev {
  opacity: 0.3 !important;
}
.carousel-control-next {
  opacity: 0.3 !important;
}
.carousel-control-next-icon {
  background-color: rgb(155, 44, 155);
  margin-bottom: 230px;
}

.roles {
  color: rgb(155, 44, 155);
  font-size: x-large;
}

.names{
  font-size: xx-large;
}
</style>
