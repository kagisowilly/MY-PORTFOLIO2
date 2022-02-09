<template>
  <section class="contact-background" id="contact" style="background-color: black">
    <div class="container justify-content-center">
      <form @submit.prevent="handleSubmit" class="contactMe">
        <h2 class="text-center display-6 fw-bold mb-3 subtitlee ">
          <u>Contact Me</u>
        </h2>
        <div id="emailHelp" class="pb-5 form-text text-center">
         <p>Let's get in touch. <br />I will never share your information with
          anyone.</p> 
        </div>

        <label class="text-white">Name:</label>
        <input  type="text" class="text-white" v-model="name" required />

        <label class="text-white">Email:</label>
        <input type="email" class="text-white" v-model="email" required />

        <label class="text-white">Subject:</label>
        <input type="text" class="text-white" v-model="subject" />

        <label class="text-white">Message:</label>

        <input type="text" class="text-white" v-model="message" />

        <div class="submit mb-5">
          <button class="rounded-pill mb-3  btn btn-warning button-body">
            <h5 id="sub" class="text-white mb-0">Submit</h5>
          </button>
        </div>

      </form>
    </div>

    <div class="container text-white">
      <div class="row text-center ">
        <div class="col-lg-4 col-sm-4 coL-md-3 ">
          <i class="bi bi-envelope contact-icons"></i>
          <h5>Email:</h5>
          <p>mphayiw@gmail.com</p>
        </div>
        <div class="col col-lg-4 col-sm-4 coL-md-3">
          <i class="bi bi-telephone-forward contact-icons"></i>
          <h5>phone Number:</h5>
          <p>(+27)79 928 2407</p>
        </div>
        <div class="col col-lg-4 col-sm-4 coL-md-6">
          <i class="bi bi-geo-alt contact-icons"></i>
          <h5>Address:</h5>
          <p>Cape Town, South Africa</p>
        </div>
      </div>
    </div>

          <div class="container">
        <hr class="my-1 bg-white" />
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
      console.log(this.name);
      console.log(this.email);
      console.log(this.subject);
      console.log(this.message);
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
input{
  display: block;
  padding: 10px 6px;
  width: 100%;
  box-sizing: border-box;
  border: none;
  border-bottom: 1px solid #ddd;
  color: #555;
  background-color: rgba(0,0,0,.25);
}


.button-body {
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
#sub:hover{
  color: rgb(0, 0, 0) !important;
}
#sub{color: white;}
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

.contact-icons{
font-size: 20px !important;
}
</style>
