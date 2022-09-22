<template>
  <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
    <div class="container">
      <a class="navbar-brand logo-text" href="#">Medical center</a>
      <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav ms-auto navbar-nav-scroll">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#header">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#details">Details</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="dropdown01" data-bs-toggle="dropdown" aria-expanded="false">Drop</a>
            <ul class="dropdown-menu" aria-labelledby="dropdown01">
              <li><a class="dropdown-item" href="#">Article Details</a></li>
              <li><div class="dropdown-divider"></div></li>
              <li><a class="dropdown-item" href="#">Terms Conditions</a></li>
              <li><div class="dropdown-divider"></div></li>
              <li><a class="dropdown-item" href="#">Privacy Policy</a></li>
            </ul>
          </li>
        </ul>
        <span class="nav-item">
              <a class="btn-solid-sm" href="#contact">Book now</a>
          </span>
      </div>
    </div>
  </nav>
  <header id="header" class="header">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <h1 class="h1-large">Best Doctors for your best health</h1>
            <p class="p-large">we will take care of you, no worries anymore stay healthy!</p>
            <a class="btn-solid-lg" href="#services">Offered services</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img style="width: 90%" src="assets/images/header-image-1.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </header>
  <div id="services" class="cards-1 bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2>Explore our services</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">


          <div class="card">
            <div class="card-icon">
              <i class="fas fa-hospital-user"></i>
            </div>
            <div class="card-body">
              <h5 class="card-title">Family Medicine</h5>
              <p>The Family Medicine clinic provides treatment for a wide range of illnesses and issues for both adults and children</p>
              <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

          <div class="card">
            <div class="card-icon red">
              <i class="fas fa-tooth"></i>
            </div>
            <div class="card-body">
              <h5 class="card-title">Dentistry</h5>
              <p>The Dentistry department provides a wide range of dental services</p>
              <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

          <div class="card">
            <div class="card-icon green">
              <i class="fas fa-syringe"></i>
            </div>
            <div class="card-body">
              <h5 class="card-title">vaccination</h5>
              <p>We know this can be a stressful time for your little ones, and we always make sure that the process is as pain free and comfortable as possible.</p>
              <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>

  <div id="details" class="basic-2">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <div class="section-title">ABOUT US</div>
            <h2>We have best doctors with +5 years experience</h2>
            <p>All of our professionals have outstanding qualifications and significant work experience in leading Western centres, including North America, Europe & Australia.</p>
            <a class="btn-outline-reg" href="#">Details</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" style="border-radius: 40%" src="assets/images/details-3.jpg" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="features" class="accordion-1">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <h2 class="h2-heading">Online service features</h2>
          <p class="p-heading">Suspendisse vitae enim arcu. Aliquam convallis risus a felis blandit, at mollis nisi bibendum. Aliquam nec purus at ex blandit posuere nec a odio. Proin lacinia dolor justo</p>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-5">
          <div class="accordion" id="accordionExample">


            <div class="accordion-item">
              <div class="accordion-icon">
                <span class="fas fa-tv"></span>
              </div>
              <div class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                  Analyse the product and design plan
                </button>
              </div>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                <div class="accordion-body">Mauris ornare libero et pharetra hendrerit. Cura elementum lectus quis tellus pretium, vitae lobortis dui sagittis aliquam et enim vel semon anticus</div>
              </div>
            </div>


            <div class="accordion-item">
              <div class="accordion-icon blue">
                <span class="fas fa-microphone"></span>
              </div>
              <div class="accordion-header" id="headingTwo">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  Find the market opportunities
                </button>
              </div>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                <div class="accordion-body">Mauris ornare libero et pharetra hendrerit. Cura elementum lectus quis tellus pretium, vitae lobortis dui sagittis aliquam et enim vel semon anticus</div>
              </div>
            </div>


            <div class="accordion-item">
              <div class="accordion-icon purple">
                <span class="fas fa-video"></span>
              </div>
              <div class="accordion-header" id="headingThree">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                  Prepare the product launch campaign
                </button>
              </div>
              <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                <div class="accordion-body">Mauris ornare libero et pharetra hendrerit. Cura elementum lectus quis tellus pretium, vitae lobortis dui sagittis aliquam et enim vel semon anticus</div>
              </div>
            </div>



            <div class="accordion-item">
              <div class="accordion-icon orange">
                <span class="fas fa-tools"></span>
              </div>
              <div class="accordion-header" id="headingFour">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                  Evaluate the campaign and adjust
                </button>
              </div>
              <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#accordionExample">
                <div class="accordion-body">Mauris ornare libero et pharetra hendrerit. Cura elementum lectus quis tellus pretium, vitae lobortis dui sagittis aliquam et enim vel semon anticus</div>
              </div>
            </div>

          </div>
        </div>
        <div class="col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/features-1.png" alt="alternative"/>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="cards-2 bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="h2-heading">Patients reviews</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
              <div class="testimonial-author">Roe Smith</div>
              <div class="occupation">General Manager, Presentop</div>
            </div>
            <div class="gradient-floor red-to-blue"></div>
          </div>


          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
              <div class="testimonial-author">Sam Bloom</div>
              <div class="occupation">General Manager, Presentop</div>
            </div>
            <div class="gradient-floor blue-to-purple"></div>
          </div>


          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
              <div class="testimonial-author">Bill McKenzie</div>
              <div class="occupation">General Manager, Presentop</div>
            </div>
            <div class="gradient-floor purple-to-green"></div>
          </div>




        </div>
      </div>
    </div>
  </div>
  <div class="slider-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h4>More than <span class="blue">10</span> branches worldwide</h4>
          <hr class="section-divider" />

          <div class="slider-container">
            <div class="swiper-container image-slider">
              <div class="swiper-wrapper">
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-1.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-2.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-3.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-4.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-5.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-6.png" alt="alternative" />
                </div>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>

  <div class="basic-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="text-container">
            <h2>Find the right solution for your pain</h2>
            <p class="p-large">Eu convallis arcu ultrices in. Mauris ornare libero et pharetra hendrerit. Curabitur elementum lectus quis vioc tellus</p>
            <a class="btn-solid-lg" href="#contact">Get free checkup</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="contact" class="form-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="text-container">
            <h3>Location</h3>
            <div class="image-container">
              <img src="assets/images/hero_geocoding_api.png" alt="alternative" />
            </div>
          </div>
        </div>
        <div class="col-lg-6">

          <form>
            <div class="form-group">
              <input type="text" class="form-control-input" placeholder="Name" required />
            </div>
            <div class="form-group">
              <input type="email" class="form-control-input" placeholder="Email" required />
            </div>
            <div class="form-group">
              <input type="text" class="form-control-input" placeholder="Industry" required />
            </div>
            <div class="form-group">
              <input type="text" class="form-control-input" placeholder="Your product" required />
            </div>
            <div class="form-group">
              <button type="submit" class="form-control-submit-button">Submit</button>
            </div>
          </form>

        </div>
      </div>
    </div>
  </div>
  <div class="footer bg-gray">
    <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h4>If you want to find out more about our services and offers don't forget to follow us</h4>
          <div class="social-container">
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-facebook-f fa-stack-1x"></i>
                      </a>
                  </span>
            <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-twitter fa-stack-1x"></i>
                      </a>
                  </span>
            <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-pinterest-p fa-stack-1x"></i>
                      </a>
                  </span>
            <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-instagram fa-stack-1x"></i>
                      </a>
                  </span>
            <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-youtube fa-stack-1x"></i>
                      </a>
                  </span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="copyright bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12">
          <ul class="list-unstyled li-space-lg p-small">
            <li><a href="#">Article Details</a></li>
            <li><a href="#">Terms & Conditions</a></li>
            <li><a href="#">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">Copyright © <a href="#">Marah Sadek </a></p>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">Distributed by <a href="https://masukmia.com" target="_blank">Marah sadek</a></p>
        </div>
      </div>
    </div>
  </div>
  <button id="myBtn">
    <img src="assets/images/up-arrow.png" alt="alternative" />
  </button>
</template>



<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
