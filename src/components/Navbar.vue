<template>
    <!-- NAVBAR -->
  <div>
    <nav
      class="navbar navbar-expand-md navbar-dark border-muted  position-fixed w-100 p-0"
      aria-label="Third navbar example"
      style="z-index: 10;
      background-color: rgb(19, 19, 19);"
    >
      <div class="container-fluid">
        <a class="nav-brand " href="#home"
          ><img
            class="navbar-brand brand img-responsive"
            src="@/assets/Logo.png"
            alt=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarsExample03"
          aria-controls="navbarsExample03"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div
          class="collapse navbar-collapse justify-content-end text-end"
          id="navbarsExample03"
        >
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#home"
                ><i class="bi bi-house-door nav-icons"></i><br />
                Home</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#about"
                ><i class="bi bi-person-lines-fill nav-icons"></i><br />
                About</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#education"
                ><i class="bi bi-pencil-square nav-icons"></i><br />
                Resume</a
              >
            </li>

            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#skills"
                ><i class="bi bi-card-list nav-icons"></i><br />
                Skills</a
              >
            </li>

            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#projects"
                ><i class="bi bi-briefcase nav-icons"></i><br />
                Projects</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#testimonials"
                ><i class="bi bi-person nav-icons"></i><br />
                Testimonials</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link active text-muted fw-bold h4"
                aria-current="page"
                href="#contact"
                ><i class="bi bi-chat nav-icons"></i><br />
                Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>

    
  </div>
</template>

<script>
const sections = document.querySelectorAll("section");
const navLi = document.querySelectorAll("nav .container ul li");
window.addEventListener("scroll", () => {
  let current = "";
  sections.forEach((section) => {
    const sectionTop = section.offsetTop;
    const sectionHeight = section.clientHeight;
    if (pageYOffset >= sectionTop - sectionHeight / 3) {
      current = section.getAttribute("id");
    }
  });

  navLi.forEach((li) => {
    li.classList.remove("active");
    if (li.classList.contains(current)) {
      li.classList.add("active");
    }
  });
});
</script>

<style>
/* .brand{
  border: solid 1px rgb(47, 47, 47);
  border-radius: 100% !important;
  height: 100px !important;
  width: 100px !important;
}
.nav.brand{
  border-radius: 100% !important;
  height:20px;
} */

</style>