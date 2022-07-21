<template>
    <nav class="navbar navbar-expand-lg fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link text-white heading" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white heading" href="/about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white heading" href="/projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white heading" href="/testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white heading" href="/resume">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white heading" href="/contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>

<script>
    export default {
        name: "Navbar"
    }
</script>


<style>
    nav {
      z-index: 999;
    }
    .navbar-brand{
      color: white;
    }
</style>