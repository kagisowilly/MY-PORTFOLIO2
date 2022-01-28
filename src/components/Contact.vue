<template>
  <section id="contact">
    <div class="container justify-content-center">
      <form @submit.prevent="handleSubmit" class="contactMe" role="form" action="https://formspree.io/f/xwkylkad" method="POST">
        <h2 class="text-center display-6 fw-bold mb-3 subtitlee ">
          <u>Contact Me</u>
        </h2>
        <div id="emailHelp" class="pb-5 form-text text-center">
          Let's get in touch. <br />I will never share your information with
          anyone.
        </div>

        <label>Name:</label>
        <input type="text" v-model="name" required />

        <label>Email:</label>
        <input type="email" v-model="email" required />

        <label>Subject:</label>
        <input type="text" v-model="subject" />

        <label>Message:</label>

        <input type="text" v-model="message" />

        <div class="submit mb-5">
          <button class="rounded-pill mb-3  btn btn-warning button-about">
            <h5 class="text-black mb-0 abt">Submit</h5>
          </button>
        </div>

      </form>
    </div>

    <div class="container">
      <div class="row text-center text-black">
        <div class="col-lg-4 col-sm-4 coL-md-3 text-black">
          <i class="bi bi-envelope"></i>
          <h5>Email:</h5>
          <p>mphayiw@gmail.com</p>
        </div>
        <div class="col col-lg-4 col-sm-4 coL-md-3">
          <i class="bi bi-telephone-forward"></i>
          <h5>phone Number:</h5>
          <p>(+27)79 928 2407</p>
        </div>
        <div class="col col-lg-4 col-sm-4 coL-md-6">
          <i class="bi bi-geo-alt"></i>
          <h5>Address:</h5>
          <p>Cape Town, South Africa</p>
        </div>
      </div>
    </div>
  </section>

  <!-- <p>Email: {{ email }}</p>
  <p>Password: {{ password }}</p>
  <p>Role: {{ role }}</p>
  <p>Terms and Conditions: {{ terms }}</p> -->
</template>

<script>
export default {
  data() {
    return {
      name: "",
      email: "",
      subject: "",
      message: "",
    };
  },
  methods: {

    handleSubmit() {
    //   console.log(this.name);
    //   console.log(this.email);
    //   console.log(this.subject);
    //   console.log(this.message);
    },
  },
};
</script>

<style>
form {
  max-width: 100%;
  margin: 30px auto;
  text-align: left;
  border-radius: 10px;
}
label {
  color: rgb(0, 0, 0);
  display: inline-block;
  margin: 25px 0 15px;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-weight: bold;
}
input,
select {
  display: block;
  padding: 10px 6px;
  width: 100%;
  box-sizing: border-box;
  border: none;
  border-bottom: 1px solid #ddd;
  color: #555;
}
input[type="checkbox"] {
  display: inline-block;
  width: 16px;
  margin: 0 10px 0 0;
  position: relative;
  top: 2px;
}
button {
  background: #0b6dff;
  border: 0;
  padding: 10px 20px;
  margin-top: 20px;
  color: white;
  border-radius: 20px;
  cursor: pointer;
}
button:hover {
  opacity: 0.8;
}
.submit {
  text-align: center;
}
.error {
  color: #ff0062;
  margin-top: 10px;
  font-size: 0.8em;
  font-weight: bold;
}
.contactMe {
  width: 100%;
  margin: 0px;
}
</style>
