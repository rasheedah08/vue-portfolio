<template>
    
      <div id="portfolio" class="row cover">
        <h2 class="text-center">Projects</h2>
        <div class="container">
          <div class="row portfolio-projects"> <!-- Two project row-->
            <div class="col-lg-6"> <!--1st side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center">
                  <h4 class="portfolio-projects--title">BMI Calculator</h4>
                  <p class="portfolio-projects--desc">Uses: Javascript, CSS, Bootstrap</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://profound-vacherin-5c0018.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center">
                  <img class="portfolio-projects--image" src="https://i.postimg.cc/CMsfdGVv/Screenshot-2022-07-21-093520.png">
                </div>
              </div>
            </div>
            <div class="col-lg-6"> <!--2nd side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center pull-right-sm"><!--flipped on small, unflipped on large-->
                  <h4 class="portfolio-projects--title">Temperature Converter</h4>
                  <p class="portfolio-projects--desc">Uses: Javascript, CSS, Bootstrap</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://rococo-choux-af10cd.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center pull-right-sm"><!--flipped on small, unflipped on large-->
                  <img class="img-rounded portfolio-projects--image" src="https://i.postimg.cc/0jvvSK7x/Screenshot-2022-07-21-093625.png">
                </div>
              </div>
            </div>
          </div><!--end Two project row-->

          <div class="row portfolio-projects"> <!-- Opposite Two project row-->
            <div class="col-lg-6"> <!--1st side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center">
                  <h4 class="portfolio-projects--title">Mock Portfolio</h4>
                  <p class="portfolio-projects--desc">Uses: HTML, CSS</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://phenomenal-piroshki-912af9.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center">
                  <img class="img-rounded portfolio-projects--image" src="https://i.postimg.cc/0N7HwWnM/Screenshot-2022-07-21-093731.png">
                </div>
              </div>
            </div>
            <div class="col-lg-6"> <!--2nd side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center pull-right-sm"><!--flipped on small, unflipped on large-->
                  <h4 class="portfolio-projects--title">End of Module protfolio</h4>
                  <p class="portfolio-projects--desc">Uses: HTML, CSS, Bootstrap</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://splendorous-pie-44f176.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center pull-right-sm"><!--flipped on small, unflipped on large-->
                  <img class="img-rounded portfolio-projects--image" src="https://i.postimg.cc/HnyZ4647/Screenshot-2022-07-21-093347.png">
                </div>
              </div>
            </div>
            <div class="col-lg-6"> <!--1st side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center">
                  <h4 class="portfolio-projects--title">Property Listing</h4>
                  <p class="portfolio-projects--desc">Uses: Javascript, CSS, Bootstrap</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://friendly-jelly-2d0462.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center">
                  <img class="portfolio-projects--image" src="https://i.postimg.cc/R0qJKJmk/Screenshot-2022-07-22-094957.png">
                </div>
              </div>
            </div>
             <div class="col-lg-6"> <!--1st side project -->
              <div class="row"> 
                <div class="col-sm-5 text-center">
                  <h4 class="portfolio-projects--title">To-do List</h4>
                  <p class="portfolio-projects--desc">Uses: Javascript, CSS, Bootstrap</p>
                  <a class="btn btn-rounded portfolio-projects--btn" href="https://leafy-praline-16a476.netlify.app/" role="button">View Project</a>
                </div>
                <div class="col-sm-7 text-center">
                  <img class="portfolio-projects--image" src="https://i.postimg.cc/J0Rp1QVw/Screenshot-2022-07-22-100022.png">
                </div>
              </div>
            </div>
          </div><!--end Opposite Two project row-->

        </div>
        </div>
      <!-- End #Portfolio -->
</template>

<style scoped>
   @import url("https://fonts.googleapis.com/css?family=Comfortaa:400,700,300|Quattrocento");

#about {
  min-height: 100vh;
}
.about-tools ul li, .contact-social-icons ul a li {
  text-align: center; }

.centered {
  float: none;
  margin-left: auto;
  margin-right: auto; }

.break {
  clear: both;
  margin-top: 10px; }

@media (min-width: 768px) {
  .pull-right-sm {
    float: right !important; }

  .pull-left-sm {
    float: left !important; } }
@media (min-width: 992px) {
  .pull-right-md {
    float: right !important; }

  .pull-left-md {
    float: left !important; } }
@media (min-width: 1200px) {
  .pull-right-lg {
    float: right !important; }

  .pull-left-lg {
    float: left !important; } }
* {
  box-sizing: border-box; }

html {
  position: relative;
  height: 100%; }

img {
  width: 90%; }


h1,
h2,
h3,
h4,
h5 {
  font-family: "Comfortaa", Helvetica, Arial, sans-serif;
  color: #07374a; }

p {
  font-family: "Quattrocento", sans-serif;
  color: #f0f0e6; }

body > .container-fluid {
  padding: 60px 15px 0; }

.container-fluid .text-muted {
  margin: 20px 0; }

.btn:focus, a:focus {
  outline: none !important; }

.navbar {
  height: 70px;
  background-color: transparent;
  background: transparent;
  border: none;
  color: #f0f0e6;
  z-index: 100;
  margin-bottom: 0;
  border-radius: 0;
  transition: background-color 1s ease 0s; }

.navbar-brand {
  display: none;
  margin-top: 10px;
  color: #f0f0e6;
  font-weight: 400; }

.navbar-default .navbar-nav > li > a {
  color: #f0f0e6;
  font-weight: 500;
  font-size: 1em;
  text-transform: lowercase;
  margin: 10px 5px 5px 5px;
  border-radius: 5px; }
.navbar-default .navbar-nav > li > a:hover, .navbar-default .navbar-nav > li > a:active, .navbar-default .navbar-nav > li > a:focus {
  color: #f0f0e6;
  border: 1px solid #f0f0e6; }
.navbar-default .navbar-nav > li > a:visited {
  color: #f0f0e6;
  text-decoration: none; }
.navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus {
  background-color: transparent;
  color: #f0f0e6; }
.navbar-default .navbar-toggle {
  border-color: #f0f0e6; }
  .navbar-default .navbar-toggle:hover, .navbar-default .navbar-toggle:focus {
    background-color: #07374a; }
  .navbar-default .navbar-toggle .icon-bar {
    color: #f0f0e6;
    background-color: #f0f0e6; }
.navbar-default .navbar-collapse.collapse.in ul {
  background-color: #07374a; }

/* Solid class attached on scroll past first section */
/* .navbar.solid {
  background-color: #07374a;
  transition: background-color 1s ease 0s;
  box-shadow: 0 0 4px rgba(7, 55, 74, 0.2); }
  .navbar.solid .navbar-brand {
    display: inline-block;
    color: #f0f0e6;
    transition: color 1s ease 0s; }
  .navbar.solid .navbar-nav > li > a {
    color: #f0f0e6;
    transition: color 1s ease 0s; } */

.cover {
  padding: 10% 0 10% 0; }
  .cover.top {
    padding: 15% 0 10% 0;
    height: 100vh;
    display: flex;
    background-color: #25b79f; }
  .cover.bottom {
    padding: 10% 0 10% 0; }

.headline {
  padding-top: 6.25em; }
  @media screen and (min-width: 768px) {
    .headline {
      padding-top: 3.75em; } }
  @media screen and (min-width: 992px) {
    .headline {
      padding-top: 1.5625em; } }
  @media screen and (min-width: 1200px) {
    .headline {
      padding-top: 0px; } }

/* #about {
  background-color: #07374a; }
  #about h2 {
    color: #25b79f; } */

/* .profile-img {
  margin-bottom: 15px;
  width: 120px; } */

/* .about, .about-info, .about-tools, .about-last {
  padding: 4% 10% 1% 10%;
  font-size: 1.25em; }
  .about-tools {
    padding-top: 4.375em;
    font-weight: 700;
    font-size: 1.5em; }
    @media screen and (min-width: 992px) {
      .about-tools {
        padding-top: 5.625em; } }
    .about-tools ul:first-child {
      padding-left: 0px; }
    .about-tools ul {
      color: #25b79f;
      list-style: none; }
      .about-tools ul li {
        padding-top: 0.75em; }
  .about-last {
    padding-top: 3.125em;
    padding-bottom: 0;
    font-size: 1.125em; }
    @media screen and (min-width: 992px) {
      .about-last {
        padding-top: 0; } }
    .about-last p {
      color: #25b79f; } */

#portfolio {
  background-color: #337595; }
  #portfolio h2 {
    padding-bottom: 1.25em; }

@media screen and (min-width: 768px) {
  .portfolio-projects {
    margin-top: 0.625em; } }
.portfolio-projects--title {
  margin-top: 0.9375em; }
  @media screen and (min-width: 768px) {
    .portfolio-projects--title {
      margin-top: 20%; } }
  @media screen and (min-width: 1200px) {
    .portfolio-projects--title {
      margin-top: 5%; } }
@media screen and (min-width: 768px) {
  .portfolio-projects--desc {
    margin-top: 10%;
    margin-bottom: 10%; } }
.portfolio-projects--btn {
  background: transparent;
  color: #07374a;
  border: 1px solid #07374a;
  border-radius: 5px;
  margin-bottom: 1.25em; }
  .portfolio-projects--btn:hover {
    background: #07374a;
    color: #f0f0e6; }
.portfolio-projects--image {
  margin-bottom: 1.875em;
  padding-top: 5%; }

/* #contact {
  background-color: #07374a; }
  #contact h2 {
    color: #25b79f; }

.contact-social-icons p {
  color: #25b79f; }
.contact-social-icons ul a {
  color: #25b79f;
  list-style: none; }
  .contact-social-icons ul a:hover {
    color: #f0f0e6; }
  .contact-social-icons ul a li {
    display: inline-block;
    padding: 2%; } */

.footer {
  bottom: 0;
  width: 100%;
  /* Set the fixed height of the footer here */
  height: 30px;
  background-color: #07374a;
  color: #f0f0e6; }

/* #scrollIcon, #scrollTopIcon {
  margin-top: 200px;
  padding: 10px;
  font-size: 1.5em;
  color: #07374a;
  border: solid 2px #07374a;
  border-radius: 50%; }

#scrollTopIcon {
  margin-top: 10px;
  font-size: 1em;
  color: #f0f0e6;
  border-color: #f0f0e6; }

.back-to-top {
  display: none; }
  .back-to-top.visible {
    display: block; } */

</style>

<script>
    
</script>
