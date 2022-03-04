<template>
  <!-- Footer -->
  <section>
    <footer
      class="page-footer font-small teal pt-2"
      style="z-index: 10; background-color: rgb(19, 19, 19)"
    >
      <div class="container text-center text-md-left">
        <div class="d-grid gap-4 d-flex justify-content-center">
          <a
            target="_blank"
            href="https://github.com/Kagisomphayi"
            class="text-muted rounded icons"
            ><i class="bi icn bi-github footer-icons"></i
          ></a>
          <a
            target="_blank"
            href="https://www.linkedin.com/in/kagiso-kagiso-5aab71219/"
            class="text-muted rounded icons"
            ><i class="bi icn bi-linkedin footer-icons"></i
          ></a>
          <a
            target="_blank"
            href="https://twitter.com/K_Mphayi"
            class="text-muted rounded icons"
            ><i class="bi icn bi-twitter footer-icons"></i
          ></a>
        </div>

        <!-- Copyright -->
        <div class="footer-copyright text-center mb-0 py-1 text-muted h5">
          ©2021 Copyright: <a href="#home" id="footerr"> Kagiso Mphayi</a>
        </div>
        <!-- Copyright -->
      </div>
    </footer>
  </section>
</template>

<script scoped>
export default {};
</script>

<style>
.hrFooter {
  margin: 0px;
  background-color: black !important;
}

#footerr:hover {
  color: white;
}
#footerr {
  color: rgb(155, 44, 155);
}
.icons:hover {
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.5);
  color: rgb(155, 44, 155) !important;
}
</style>
