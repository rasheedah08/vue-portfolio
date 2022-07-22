<template>
  <div class="bg-gradient text-white text-center py-4" id="testimonials">
    <div class="container">
      <h2>TESTIMONIALS</h2>
      <div class="row">
        <div class="col d-flex justify-content-center">
          <div class="box-testimonial 2" data-aos="fade-right">
            <h3>Sibongile Rwayi</h3>
            <div class="row">
              <div class="col-md-6">
                <img
                  src="https://i.postimg.cc/y8S05hhP/Sibongile.jpg"
                  alt=""
                  width="60%"
                  height="auto"
                  class="img-fluid"
                />
              </div>
              <div class="col-md-6">
                <p class="reference">
                  Rasheedah is an an amazing individual to work with - hard
                  working, curious to learn, and a people's person. She shows a
                  lot of great potential and indeed has a very bright future. -
                  PEER
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col d-flex justify-content-center">
          <div class="box-testimonial 2" data-aos="fade-left">
            <h3>Joel Mukanya</h3>
            <div class="row">
              <div class="col-md-6">
                <img
                  src="https://i.postimg.cc/6QQ41X9J/joel2.jpg"
                  alt=""
                  width="60%"
                  class="img-fluid"
                />
              </div>
              <div class="col-md-6">
                <p class="reference">
                  Rasheedah demonstrates a fantastic understanding of the
                  materials we are learning in class. Rasheedah has proven to
                  have an exhaustive understanding of the HTML, CSS & Bootstrap
                  topics we covered.Joel Mukanya-CODING LECTURER
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col d-flex justify-content-center">
          <div class="box-testimonial 2" data-aos="fade-right">
            <h3>Philani Mxathule</h3>
            <div class="row">
              <div class="col-md-6">
                <img
                  src="https://i.postimg.cc/y88rnDSV/Philani-3.jpg"
                  alt=""
                  width="60%"
                  class="img-fluid"
                />
              </div>
              <div class="col-md-6">
                <p class="reference">
                  Rasheedah is a hard working individual. she is humble and
                  passionate about coding apart from that she is a nice person
                  and she likes to smile and she treats everyone eqaully. - PEER
                </p>
              </div>
            </div>
          </div>
        </div>
         <div class="col d-flex justify-content-center">
          <div class="box-testimonial 2" data-aos="fade-left">
             <h3>Taucia Jackson</h3> 
             <div class="row">
               <div class="col-md-6">
                 <img src="https://i.postimg.cc/W1dTNNSp/taucia-png.jpg" alt=""  class="img-fluid" width="60%">
               </div>
               <div class="col-md-6">
                 <p  class="reference">Rasheeedah is a very hard working person, always focused and does her best in everything she gets. She is dedicated to finish every task and is always cheerful. - PEER</p>
               </div>
             </div>
          </div>
      </div>
        <div class="col d-flex justify-content-center">
          <div class="box-testimonial 2" data-aos="fade-left">
            <h3>Meagan Williams</h3>
            <div class="row">
              <div class="col-md-6">
                <img
                  src="https://i.postimg.cc/j2MjdjNc/Meagan-2.jpg"
                  alt=""
                  width="60%"
                  class="img-fluid"
                />
              </div>
              <div class="col-md-6">
                <p class="reference">
                  Rasheedah is a very quick leaner and has a wonderful eye for
                  design, at times she seems very tired, but thats because she
                  really goes the extra mile and puts in her all, a wonderful
                  person to work with - PEER
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col d-flex justify-content-center">
        <div class="box-testimonial 2" data-aos="fade-right">
           <h3>Saleem Ariefdien</h3> 
           <div class="row">
             <div class="col-md-6">
               <img src="https://i.postimg.cc/52BpFvss/Saleem.jpg"  alt="" width="60%"
               class="img-fluid">
             </div>
             <div class="col-md-6">
               <p  class="reference">Rasheedah is a  person who is always willing to lend a helping hand.  She works hard and always puts in 100% effort . She would be a good person to have at your company. - PEER</p>
             </div>
           </div>
        </div>
    </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Comfortaa:400,700,300|Quattrocento");
#testimonials {
    min-height: 100vh;
}

.about-tools ul li,
.contact-social-icons ul a li {
  text-align: center;
}

.heading {
  font-family: "Quattrocento", sans-serif;
  color: #f0f0e6;
}

h1,
h2,
h3,
h4,
h5 {
  font-family: "Comfortaa", Helvetica, Arial, sans-serif;
  color: #07374a;
}

p {
  font-family: "Quattrocento", sans-serif;
  color: #f0f0e6;
}

.box {
  height: 90%;
  width: 80%;
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 80px;
  margin: 10px;
  padding: 20px;
}
.box-testimonial {
  height: 300px;
  width: 500px;
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  margin: 20px;
  padding: 20px;
}

@media all and (max-width: 768px) {
  .box-testimonial {
    height: 300px;
    width: 500px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 20px;
    margin: 10px;
    padding: 20px;
  }
  .reference {
    padding-top: 10px;
  }
  .img-fluid {
    width: 200px;
    object-fit: cover;
  }
}
@media all and (max-width: 567px) {
  .box-testimonial {
    height: 300px;
    width: 500px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 20px;
    margin: 10px;
    padding: 20px;
  }
  .reference {
    padding-top: 10px;
  }
  .img-fluid {
    width: 200px;
    object-fit: cover;
  }
}
@media all and (max-width: 400px) {
  .box-testimonial {
    height: auto;
    width: 350px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 20px;
    margin: 10px;
    padding: 20px;
  }
  .reference {
    padding-top: 10px;
  }
  .img-fluid {
    width: 200px;
    object-fit: cover;
  }
}
@media (max-width: 350px) {
  .box-testimonial {
    width: 300px;
    height: 500px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 20px;
    margin: 10px;
    padding: 20px;
  }
  .reference {
    padding-top: 10px;
  }
  .img-fluid {
    width: 200px;
    object-fit: cover;
  }
}
</style>

<script></script>
