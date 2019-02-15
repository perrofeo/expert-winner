<template>
  <div>
    <div class="fondo-contact">
  <b-navbar toggleable type="light" variant="light">
    <b-navbar-brand href="#">
      <img src="https://placekitten.com/g/30/30" class="d-inline-block align-top" alt="BV" />
    </b-navbar-brand>
    <b-navbar-nav class="ml-auto">
    <b-nav-item href="/" right>back to Home</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
  <div class="container">
    <div class="fondo-color">
      <h1 class="title">
        Food Forest in Panama
      </h1>
      <h2 class="subtitle">
        with Ron Hunter and James Brown
      </h2>
    </div>
  </div>
  </div>
  <div class="info text-center">
      <h1>Info & Contact</h1>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quod cumque quae blanditiis libero facere eos ratione asperiores eius, illo magni nesciunt ad debitis dolorem explicabo impedit amet dolorum? Doloremque, velit?</p>
  </div>
  <div class="contacto text-center">
        <a v-b-popover.hover="'I am popover content!'" title="Popover Title" href=""><img src="~assets/YouTube.png" alt="logo youtube"></a>
        <p>Take a look in our <a href="#">Youtube Channel</a> and, why not, <a href="#">subscribe</a>.</p>
      </div>
  </div>
</template>

<style>
.fondo-contact {
  background-image: url('~assets/test_portada2.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-width: 100%;
  background-blend-mode: darken;
}
.fondo-color {
  padding: 50px;
  height: 60vh;
}
.bg-light {
  background-color: transparent !important;
}
.fondo-contact .nav-link {
  color: white !important;
}
.container {
  margin: 0 auto;
  /* min-height: 100vh; */
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 60px;
  color: white;
  letter-spacing: 1px;
  padding-top: 0px;
}

.subtitle {
  font-weight: bold;
  font-size: 20px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.info {
  padding-top: 40px;
  max-width: 500px;
  margin: auto;
}
.contacto {
  width: 100%;
  padding: 0 0 40px;
}
.contacto img {
  width: 110px;
  padding: 0px 0 0px;
}
.contacto a {
  color: #d52423;
}
@media (max-width: 750px) {
  .title {
    font-size: 40px;
  }
  .subtitle {
    font-size: 16px;
  }
}
</style>
