<script setup></script>

<template>
  <div class="container-fluid p-0 mb-5 responsive-hero">
    <div class="page-header position-relative">
      <div class="position-relative">
        <img class="img-fluid hero-image" src="../assets/img/carousel-1.jpg" alt="child playing" />
        <div
          class="position-absolute top-0 start-0 w-100 h-100 d-flex align-items-center"
          style="background: rgba(0, 0, 0, 0.2)"
        >
          <div class="container hero-container">
            <div class="row justify-content-start">
              <div class="col-10 col-lg-8">
                <h1 class="display-2 text-white animated slideInDown mb-4">
                  Cabinet de Psychomotricité à Chateaurenard
                </h1>
                <p class="fs-5 fw-medium text-white mb-4 pb-2">
                  Charlotte Lumeau, Psychomotricienne D.E
                </p>
                <p class="fs-5 fw-medium text-white mb-4 pb-2">Villa Medica</p>
                <p class="fs-5 fw-medium text-white mb-4 pb-2">07 65 74 20 78</p>
                <a
                  href="#soins"
                  class="btn btn-primary rounded-pill py-sm-3 px-sm-5 me-3 animated slideInLeft"
                  >Les soins</a
                >
                <a
                  href="#aPropos"
                  class="btn btn-dark rounded-pill py-sm-3 px-sm-5 animated slideInRight"
                  >Qui suis-je?</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container-xxl py-5" id="soins">
    <div class="container">
      <div
        class="text-center mx-auto mb-5 wow fadeInUp main-page-title"
        data-wow-delay="0.1s"
        style="max-width: 600px"
      >
        <h1 class="mb-3">Les soins</h1>
      </div>
      <div class="row g-4 d-flex justify-content-around">
        <div class="col-lg-3 col-sm-6 wow fadeInUp" data-wow-delay="0.1s">
          <div class="facility-item">
            <div class="facility-icon bg-primary">
              <i class="fa fa-file-medical fa-3x text-primary"></i>
            </div>
            <div class="facility-text bg-primary">
              <h3 class="text-primary mb-3">Bilan psychomoteur</h3>
              <p class="mb-0">
                Se déroule en trois temps, rencontre/anamnèse, passation des épreuves, restitution
                écrite et orale.
              </p>
              <p class="mb-0">Durée : 1h00 / 3 séances</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6 wow fadeInUp" data-wow-delay="0.3s">
          <div class="facility-item">
            <div class="facility-icon bg-success">
              <i class="fa fa-diagnoses fa-3x text-success"></i>
            </div>
            <div class="facility-text bg-success">
              <h3 class="text-success mb-3">Séances psychomotrices</h3>
              <p class="mb-0">
                Rééducation des troubles psychomoteurs, éducation précoce, thérapie à approche
                corporelle, graphomotricité.
              </p>
              <p class="mb-0">Durée : 45 minutes</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6 wow fadeInUp" data-wow-delay="0.5s">
          <div class="facility-item">
            <div class="facility-icon bg-warning">
              <i class="fa fa-baby fa-3x text-warning"></i>
            </div>
            <div class="facility-text bg-warning">
              <h3 class="text-warning mb-3">Eveil psychomoteur</h3>
              <p class="mb-0">
                Séance parent-bébé pour favoriser le développement psychomoteur de votre tout petit
                et vous transmettre des outils adaptés.
              </p>
              <p class="mb-0">Durée : Adapatée aux besoins</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-xxl py-5" id="aPropos">
    <div class="container">
      <div class="row g-5 align-items-center">
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
          <h1 class="mb-4">Qui suis-je?</h1>
          <p class="mb-4">
            Diplômée de l'ISRP de Paris en 2014, je bénéficie d'une expérience institutionnelle
            auprès de différents publics ainsi que de plusieurs années d'exercice en cabinet libéral
          </p>
          <p class="mb-4">
            Passionnée par mon métier, je réalise chaque année une ou plusieurs formations
            complémentaires afin d'affiner ma pratique et de répondre au mieux aux besoins des
            patients. Je me tiens informée de l'évolution des recommandations de bonnes pratiques de
            la Haute Autorité de santé, notamment à travers ma participation régulière à différents
            colloques/ conférences. Je suis également membre de l'association française des
            psychomotriciens libéraux.
          </p>
          <div class="row g-4 align-items-center">
            <div class="col-sm-6">
              <a class="btn btn-primary rounded-pill py-3 px-5" href="./pages/about.html"
                >Quand consulter?</a
              >
            </div>
            <div class="col-sm-6">
              <div class="d-flex align-items-center">
                <img
                  class="rounded-circle flex-shrink-0"
                  src="../assets/img/Logo_resized.png"
                  alt="Charlotte's portrait"
                  style="width: 45px; height: 45px"
                />
                <div class="ms-3">
                  <h6 class="text-primary mb-1">Charlotte Lumeau</h6>
                  <small>Psychomotricienne</small>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 about-img wow fadeInUp" data-wow-delay="0.5s">
          <div class="row">
            <div class="col-12 text-center">
              <img
                class="img-fluid w-50 bg-light p-3"
                src="../assets/img/cabinet/activites.jpg"
                alt="salle_d_attente"
              />
            </div>
            <div class="col-6 text-start" style="margin-top: -150px">
              <img
                class="img-fluid w-75 bg-light p-3"
                src="../assets/img/cabinet/bureau.jpg"
                alt="bureau"
              />
            </div>
            <div class="col-6 text-end" style="margin-top: -150px">
              <img
                class="img-fluid w-75 bg-light p-3"
                src="../assets/img/cabinet/salle_attente.jpg"
                alt="espace_de_soins"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container-xxl py-5" id="map">
    <div class="container">
      <h2 class="mb-4 text-center">Où me trouver?</h2>
      <div class="bg-light rounded">
        <div class="row g-0">
          <div class="col-lg-6 wow fadeIn" data-wow-delay="0.1s" style="min-height: 400px">
            <div class="position-relative h-100">
              <img
                class="position-absolute w-100 h-100 rounded"
                src="../assets/img/map_2.webp"
                style="object-fit: cover"
                alt="map"
              />
            </div>
          </div>
          <div class="col-lg-6 wow fadeIn" data-wow-delay="0.5s">
            <div class="h-100 d-flex flex-column justify-content-center p-5">
              <div
                class="container d-flex justify-content-center flex-column align-items-center text-center"
              >
                <h2 class="mb-4 fs-1">Villa Medica</h2>
                <h5 class="mb-4 fs-3">16 BOULEVARD GAMBETTA</h5>
                <h5 class="mb-4 fs-2">13160 CHATEAURENARD</h5>
                <p class="mb-4">Parking gratuit derrière le centre médical</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container-xxl py-5" id="contactForm">
    <div class="container">
      <div class="bg-light rounded">
        <div class="row g-0">
          <div class="col-lg-6 wow fadeIn" data-wow-delay="0.1s">
            <div class="h-100 d-flex flex-column justify-content-center p-5">
              <h1 class="mb-4">Me contacter</h1>
              <form id="contact-form" onsubmit="sendEmail();">
                <div class="row g-3">
                  <div class="col-sm-6">
                    <div class="form-floating">
                      <input
                        type="text"
                        class="form-control border-0"
                        name="name"
                        placeholder="Nom, prénom"
                        id="name"
                      />
                      <label for="name">Nom, Prénom</label>
                    </div>
                  </div>
                  <div class="col-sm-6">
                    <div class="form-floating">
                      <input
                        type="email"
                        class="form-control border-0"
                        name="email"
                        placeholder="Email"
                        id="email"
                      />
                      <label for="email">Email</label>
                    </div>
                  </div>
                  <div class="col-sm-6">
                    <div class="form-floating">
                      <input
                        type="text"
                        class="form-control border-0"
                        name="childName"
                        placeholder="Prénom de l'enfant"
                        id="childName"
                      />
                      <label for="childName">Prénom de l'enfant</label>
                    </div>
                  </div>
                  <div class="col-sm-6">
                    <div class="form-floating">
                      <input
                        type="text"
                        class="form-control border-0"
                        name="childAge"
                        placeholder="Date de naissance de l'enfant"
                        pattern="\d{1,2}/\d{1,2}/\d{4}"
                        id="childAge"
                      />
                      <label for="childAge">Date de naissance</label>
                    </div>
                  </div>
                  <div class="col-12">
                    <div class="form-floating">
                      <textarea
                        class="form-control border-0"
                        name="message"
                        placeholder="Ecrivez votre message ici"
                        style="height: 100px"
                        id="message"
                      ></textarea>
                      <label for="message">Message</label>
                    </div>
                  </div>
                  <div class="col-12">
                    <button class="btn btn-primary w-100 py-3" type="submit">Envoyer</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
          <div class="col-lg-6 wow fadeIn" data-wow-delay="0.5s" style="min-height: 400px">
            <div class="position-relative h-100">
              <img
                class="position-absolute w-100 h-100 rounded"
                src="../assets/img/mike-meyers-haAxbjiHds-unsplash.webp"
                style="object-fit: cover"
                alt="yellow phone"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
