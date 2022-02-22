<template>
  <!-- Testimonials -->
  <section
    class="testimonial-background"
    style="background-color: black"
    id="testimonials"
  >
    <div class="container">
      <h1 class="text-center display-6 mb-5 fw-bold subtitlee">
        <u>Testimonials</u>
      </h1>
      <div
        id="carouselExampleControlsNoTouching"
        class="carousel testi slide text-black col-lg-10"
        data-bs-touch="false"
        data-bs-interval="false"
      >
        <div class="row text-center">
          <div
            class="carousel-inner text-white"
            v-for="(testimonial, index) in testimonials"
            :key="index"
          >
            <div
              class="carousel-item mt-5"
              :class="{ active: index == isActive }"
            >
              <img
                :src="testimonial.image"
                class="d-block img-thumbnail"
                alt="..."
              />
              <div class="text-center mt-5 ">
                <p class="h5 names text-center mt-3">{{ testimonial.name }}</p>
                <b class="roles">{{ testimonial.role }}</b>
                <div class=" ">
                  <p class="text-center mt-3">{{ testimonial.description }}</p>
                </div>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            @click="changePrevTesimonial"
            data-bs-target="#carouselExampleControlsNoTouching"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            @click="changeNextTesimonial"
            data-bs-target="#carouselExampleControlsNoTouching"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      isActive: 0,
      testimonials: null,
    };
  },
  methods: {
    changeNextTesimonial() {
      if (this.isActive < 5) this.isActive++;
      else this.isActive = 0;
    },
    changePrevTesimonial() {
      if (this.isActive < 6) {
        this.isActive--;
      }
      if (this.isActive < 0) {
        this.isActive = 5;
      }
    },
  },

    mounted() {
    fetch("https://kagisomphayiportfolio.herokuapp.com/testimonials")
      .then((res) => res.json())
      .then((data) => {
        console.log(data);
        this.testimonials = data;
      });
  },
};
</script>

<style>
.d-block {
  border-radius: 50%;
  height: 200px;
  margin: auto;
  width: 200px;
  object-fit: cover;
}
.carousel-item {
  /* background-color: #d4d9df; */
  border-radius: 15px;
  height: 500px;
}

.carousel-control-prev-icon {
  background-color: rgb(155, 44, 155);
  margin-bottom: 230px;
}
.carousel{
  margin-top:150px;
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

.names {
  font-size: xx-large;
}

.carousel-control-next-icon:hover {
  background-color: white;
}
.carousel-control-prev-icon:hover {
  background-color: white;
}
.description {
  width: 700px !important
  ;
}
</style>
