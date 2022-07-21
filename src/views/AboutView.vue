<template>
  <div  class="container">
    <div class="row">
      <div class="about-content animated fadeIn scrollable">
        <h1 class="animated fadeIn one">About myself</h1>
        <div
          class="about-me"
          style="transform: translateY(0px) translateZ(0px); margin-top: 20px"
        >
          <div class="animated fadeIn two">
             I enjoy new things and meeting new people. I would say im an adventurous person and an adrenaline junkie. I enjoy sports or any outdoor activities for that matter. I enjoy sightseeing and going to the beach, my hobbies also include baking , which i have done for a while by selling baked goods and desserts for various occations . I enjoy retail therapy which just lets my love for fashion grow.
          </div>
          <div
            class="Synopsis-highlightLine five"
            style="transform: matrix(1, 0, 0, 1, 0, 0)"
          ></div>
          <div class="animated fadeIn three">
            <p class="Synopsis-highlight">I matriculated at South Peninsula High School in 2021 and decided to
            take a gap year to figure out what i actually want to do with my
            life. I then got the opportunity to study at Life Choices coding
            academy in March 2022 . I started here with no coding background at
            all , but as time passed i grew to enjoy all the challenges and
            started to understand what web development is all about .</p>
          </div>
          <div
            class="Synopsis-highlightLine five"
            style="transform: matrix(1, 0, 0, 1, 0, 0)"
          ></div>
          <div class="animated fadeIn four">
            <p>
              I found a love for fashion at a very young age. I would always cut up material to make clothing for my dolls. Recently i started attending sewing classes which taught me to make clothing on a more professional level. I am now doing a designing course alongside my coding course .
            </p>
          </div>
        </div>
      </div>
      <div class="about-panel-wrapper">
        <div class="about-panel animated fadeIn">
          <div class="perspective-container">
            <div
              class="zero photo-about animated fadeIn"
              style="transform: translateY(0px) translateZ(0px)"
            >
              <div class="hide-photo-filter animated fadeIn"></div>
              <div class="about-info">
                <h3 class="about-info-name animated fadeInUp up-one text-white">
                  RASHEEDAH ANHUIZEN
                </h3>
                <div class="about-info-contact">
                  <h4 class="animated fadeInUp up-two text-white">
                    Aspiring Developer, Ocassional Seamstress, Adrenaline
                    junkie.
                  </h4>
                  <p class="animated fadeInUp up-three text-white">
                    414 3rd Avenue Grassy Park, Cape Town
                  </p>
                  <a href="" class="animated fadeInUp up-four text-white"
                    >rasheedahanhuizen@gmail.com</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* $moveup: up-two up-three up-four;

$break-small: 450px;
$break-large: 1199px;

$pink: #FF1EAD;
$dark-purp:#4B384C;
$med-purp:#632C65;
$light-purp: #E2A9E5; */

/*  About Page animation for content  */
@mixin respond-to($media) {
  @if $media == handhelds {
    @media only screen and (max-width: $break-small) {
      @content;
    }
  } @else if $media == medium-screens {
    @media only screen and (min-width: $break-small + 1) and (max-width: $break-large - 1) {
      @content;
    }
  } @else if $media == wide-screens {
    @media only screen and (min-width: $break-large) {
      @content;
    }
  }
}

@import url("https://fonts.googleapis.com/css?family=Comfortaa:400,700,300|Quattrocento");
.about-tools ul li, .contact-social-icons ul a li {
  text-align: center; }

.heading{
  font-family: "Quattrocento", sans-serif;
  color: #f0f0e6;
}

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

  


html,
body {
  height: 100vh;
  width: 100%;
  margin: 0;
  padding: 0;
}



.row {
  margin: 0;
}

.about-content,
.about-panel {
  max-width: 50%;
  width: 50%;
}

.container {
  margin: 0;
  padding: 0;
  background-color: rgba(233, 150, 122, 0.2);
  overflow-y: auto;
  height: 100vh;
  max-width: 100%;
}

.about-panel {
  padding: 0;
  position: absolute;
  top: 0;
  right: 0;
  -webkit-animation: example 1.2s both ease-in;
  -moz-animation: example 1.2s both ease-in;
  animation: example 1.2s both ease-in;
  height: 100vh;
}

.photo-about {
  position: relative;
  top: 0;
  height: 100vh !important;
  background-size: cover;
  overflow: hidden;
}

.about-info {
  font-family: "Montserrat";
  position: absolute;
  /* z-index: 100100; */
  top: 50%;
  color: white;
  text-align: center;
  width: 100%;
}

.about-info-name {
  width: 100%;
  letter-spacing: 3px;
  font-weight: 500;
  font-size: 2.5vw;
}

.about-info-contact {
  margin-top: 25px;
  padding-bottom: 100px;
  margin-bottom: 100px;
  height: 130px;
}

h4 {
  margin-bottom: 5px;
  font-weight: 300;
  font-size: 1.3vw;
}

p {
  font-size: 1.2vw;
  font-weight: 100;
  color: #b5b5b5;
  margin-top: 10px;
  margin-bottom: 0;
}

a {
  margin-bottom: 5px;
  font-weight: 300;
  font-size: 1.2vw;
  color: light-purp;
}

.about-content {
  float: left;
  padding-top: 30px;
  color: dark-purp;
}

blockquote {
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 0.07em;
}

h1 {
  z-index: -1;
  color: med-purp;
  text-align: center;
  line-height: 90px;
  font-size: 90px;
  font-weight: 200;
  letter-spacing: -0.1em;
  width: 95%;
  margin-bottom: 10px;
  margin-top: 10px;
}

@include respond-to(handhelds) {
  padding-left: 40px;
  padding-right: 40px;
}

.about-me {
  margin: 3% auto;
  text-align: justify;
  font-weight: 300;
  width: 63%;
}

p {
  line-height: 23px;
}
.row {
  height: 100vh;
}

.Synopsis-highlightLine {
  width: 52px;
  height: 4px;
  background: med-purp;
  margin: 30px 0;
}

.Synopsis-highlight {
  font-weight: 700 !important;
  font-size: 15px !important;
  line-height: 25px !important;
  width: 100%;
  color: med-purp;
}

/* Generates animations for cascading tiles */
.about-panel {
  @for $i from 1 through length($moveup) {
    $item: nth($moveup, $i);
    height: 100%;

    .about-info-contact {
      display: block;
      margin: 30px;
    }

    /* .about-info-contact .#{$item} {
			-webkit-animation-delay: #{$i * 0.08s};
			-moz-animation-delay: #{$i * 0.08s};
			animation-delay: #{$i * 0.08s};
			transition-timing-function: cubic-bezier(0.42,0,0.58,1);
			display:block;
		} */
  }
}

.perspective-container {
  transform: matrix(1, 0, 0, 1, 0, 0) !important;
}

.photo-about {
  /* background: url("https://i.postimg.cc/qRcGLyYN/Rasheedah-2.jpg") no-repeat center center; */
  background-size: 50vh;
  /* z-index: 45; */
}

.hide-photo-filter {
  /* position: relative; */
  /* top: 0; */
  /* background-color: rgba(255, 30, 173, 0.2); */
  /* background-image: url(
    "https://i.postimg.cc/qRcGLyYN/Rasheedah-2.jpg",
    linear-gradient(rgba(255, 30, 173, 0.2))
  ); */
   background-image: linear-gradient(rgba(255, 30, 173, 0.2), rgba(0, 0, 0, 0.2)), url("https://i.postimg.cc/gkgsX6rY/IMG-0312.jpg");
   background-repeat: no-repeat;
   background-size: cover;
    
  /* z-index: 50; */
  width: 100%;
  height: 100%;
}
</style>

<script>

</script>
