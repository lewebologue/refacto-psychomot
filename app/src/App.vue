<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="container-xxl bg-white p-0">
    <!-- <div
      id="spinner"
      class="show bg-white position-fixed translate-middle w-100 vh-100 top-50 start-50 d-flex align-items-center justify-content-center">
      <div class="spinner-border text-primary" style="width: 3rem; height: 3rem" role="status">
        <span class="sr-only">Loading...</span>
      </div>
    </div> -->
    <nav class="navbar navbar-expand-lg bg-white navbar-light sticky-top px-4 px-lg-5 py-lg-0">
      <img src="./assets/img/Logo_resized.png" class="logo" alt="logo" />
      <a href="index.html" class="navbar-brand">
        <h2 class="m-0 text-primary">Charlotte Lumeau</h2>
      </a>
      <button
        type="button"
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarCollapse"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <div class="navbar-nav ms-auto">
          <a href="./pages/about.html" class="nav-item nav-link d-flex justify-content-end"
            >Quand consulter?</a
          >
          <a href="./pages/parcours.html" class="nav-item nav-link d-flex justify-content-end"
            >Mon parcours</a
          >
          <a href="#map" class="nav-item nav-link d-flex justify-content-end">Où me trouver?</a>
          <a
            href="https://docorga.com/praticien/62cd6595ac9ec0761018cbd2"
            target="_blank"
            class="nav-item nav-link d-flex justify-content-end booking"
            id="booking-btn"
            >Prendre RDV</a
          >
        </div>
        <a
          href="https://docorga.com/praticien/62cd6595ac9ec0761018cbd2"
          target="_blank"
          class="btn btn-primary rounded-pill px-3 d-none d-lg-block"
          >Prendre RDV<i class="fa fa-arrow-right ms-3"></i
        ></a>
      </div>
    </nav>
  </div>

  <RouterView />

  <div
    class="container-fluid bg-dark text-white-50 footer pt-4 mt-4 wow fadeIn"
    data-wow-delay="0.1s"
  >
    <div class="container py-5">
      <div class="row g-1">
        <div class="col-lg-3 col-md-6">
          <h3 class="text-white mb-4">Me contacter</h3>
          <p class="mb-2">
            <i class="fa fa-map-marker-alt me-3"></i>Villa medica<br />16 boulevard Gambetta<br />13160
            Chateaurenard
          </p>
          <p class="mb-2"><i class="fa fa-phone-alt me-3"></i>07 65 74 20 78</p>
          <p class="mb-2">
            <i class="fa fa-envelope me-3"></i>contact@psychomotrice-villamedica.fr
          </p>
        </div>
        <div class="col-lg-3 col-md-6">
          <h3 class="text-white mb-4">Liens utiles</h3>
          <a class="btn btn-link text-white-50" href="./pages/legal.html">Mentions légales</a>
          <a class="btn btn-link text-white-50" href="#contact-form">Contact</a>
          <a class="btn btn-link text-white-50" href="./pages/confidential.html"
            >Politique de confidentialité</a
          >
        </div>
      </div>
    </div>
  </div>

  <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top" id="scrollTop"
    ><i class="bi bi-arrow-up"></i
  ></a>
</template>
