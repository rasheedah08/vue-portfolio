<template>
  <section class="landing" id="landing">
      <h1>Hi, I'm Rasheedah Anhuizen</h1>
      <h3>Aspiring Web Developer</h3>
  </section>
</template>

<script>
// @ is an alias to /src


// export default {
//   name: 'HomeView',
//   components: {

//   }
// }
</script>

<style scoped>
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

#landing{
  min-height: 100vh;
  background-image: url("https://i.postimg.cc/ZnkVtZNB/2-22302-best-hd-sky-wallpapers-for-pc-mac-tablet.jpg");
  background-size: cover;
  /* background-position: center; */
  background-attachment: fixed;
  /* display: flex;
  justify-content: center; */
}
.landing h1{
  position: absolute;
  top: 40%;
  left:33%;
  color: white;
}

.landing h3{
  position: absolute;
  top: 50%;
  left:39%;
  color: white;
  
}


@media all and (max-width: 544px) {
.landing h1{
  font-size: 22px;
  /* position: relative; */
}

}

</style>
