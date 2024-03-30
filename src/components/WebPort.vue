<template>
  <nav class="navbar navbar-expand-lg sticky-top p-3" style="background-color: #46494C;">
      <div class="container-fluid">
          <a class="navbar-brand text-light fs-5 ms-4 me-auto" href="#home">My Portfolio</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
              aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
              <ul class="navbar-nav me-4">
                  <li class="nav-item">
                      <a class="nav-link text-light fs-6" aria-current="page" href="#about">About</a>
                  </li>
                  <li class="nav-item">
                      <a class="nav-link text-light fs-6" href="#skills">Skills</a>
                  </li>
              </ul>
          </div>
      </div>
  </nav>

  <div id="home" class="container p-5 mt-5">
      <div class="row justify-content-center">
          <div class="col-md-4">
              <div class="card bg-light p-3">
                  <img class="card-img-top rounded" alt="Portrait" src="/profile.jpg">
              </div>
          </div>
          <div class="col-md-6">
              <h2 class="fw-bold mb-5 mt-5">John Reil Degamo</h2>
              <div class="row">
                  <div class="col-md-12">
                      <h5>
                          Greetings! I'm John Reil Degamo, a dedicated student hailing from <a class="text-dark fw-bold text-decoration-none" href="https://www.facebook.com/cpcofficial2005"> Cordova Public College</a>, where I'm actively pursuing studies in computer science.
                      </h5>
                  </div>
                  <div class="col-md-12 mt-4">
                      <h5>
                          I possess a strong knack for design and am adept at tackling diverse challenges. Proficient in several programming languages, I'm fueled by a passion for continuous learning and growth within the dynamic landscape of technology.
                      </h5>
                  </div>
              </div>
          </div>
      </div>
  </div>


  <div class="text-white p-5" id="about" style="background-color: #4c5c68;">
      <h2 class="p-3 text-center fw-bold">About Me</h2>

      <div class="container mb-4 p-5">
          <p class="fs-5">
              Greetings! I am John Reil Degamo, an impassioned and dedicated programmer committed to curating 
              exceptional web experiences. My expertise spans both frontend and backend development, 
              where I meticulously transform concepts into reality, crafting intuitive interfaces that 
              resonate with users.
          </p>
          <p class="fs-5">
              What distinguishes me is not only my technical acumen but also my dedication to 
              effective communication and strategic planning. I am adept at discerning the distinct 
              requirements of each project, delivering solutions that surpass expectations. 
              From initial ideation to final execution, I ensure each aspect of the project is executed 
              meticulously to achieve optimal outcomes.
          </p>
          <p class="fs-5">
              My skill set encompasses proficiency in a diverse array of technologies, 
              including HTML, CSS, PHP, BOOTSTRAP and more. 
              Whether you seek a responsive website, dynamic web application, or bespoke software solution, 
              I am poised to bring your vision to fruition. Furthermore, 
              I offer comprehensive services such as website maintenance, performance optimization, 
              and security enhancements to uphold the excellence of your digital presence.
          </p>
      </div>
  </div>

  <h2 id="skills" class="pt-4 mb-4 text-center fw-bold">Skills</h2>

      <div class="container">
          <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
              <div class="col-lg-3 col-md-4 text-center py-4 my-3">
                  <img src="bootstrap.png" width="80px" title="Bootstrap" class="zoom-in-effect">
              </div>
              <div class="col-lg-3 col-md-4 text-center py-4 my-3">
                  <img src="css.png" width="80px" title="CSS" class="zoom-in-effect">
              </div>
              <div class="col-lg-3 col-md-4 text-center py-4 my-3">
                  <img src="php.png" width="140px" title="PHP" class="zoom-in-effect">
              </div>
              <div class="col-lg-3 col-md-4 text-center py-4 my-3">
                  <img src="html.png" width="80px" title="HTML" class="zoom-in-effect">
              </div>
          </div>
      </div>


      <footer style="background-color: #efd28d; padding: 2px 0;">
          <div class="container-fluid">
              <div class="row">
                  <div class="col-lg-6 col-md-2 text-start py-2 my-1">
                      <a class="me-3 ms-4" href="https://www.facebook.com/profile.php?john.reil.984" target="_blank">
                          <img src="fb.png" width="30px" title="Facebook" class="zoom-in-effect">
                      </a>
                      <a class="me-3" href="https://www.instagram.com/janlir13/">
                          <img src="ig.png" width="30px" title="Instagram" class="zoom-in-effect">
                      </a>
                      <a href="mailto:johndegamo55@gmail.com" class="text-dark text-decoration-none" target="_blank">
                          <img src="email.png" width="30px" title="Gmail" class="zoom-in-effect">
                      </a>
                  </div>
              </div>
          </div>
      </footer>





</template>

<script>

</script>


<style>

.navbar-brand, .nav-link {
  font-family: sans-serif;
  font-size: 10px; 
}

body {
  font-family: 'Times New Roman', Times, serif;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* Adding shadow to the card */
  padding: 30px; /* Adding padding to the card */
}

.card-img-top {
  width: 100%; /* Set image width to 100% */
  height: 400px; /* Maintain aspect ratio */
}


h1,
h5 {
  font-size: 15px; /* You can adjust the font size as needed */
}

</style>
