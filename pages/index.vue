<template>
  <div class="fondo-home">
  <b-navbar toggleable type="light" variant="light">
    <b-navbar-brand href="#">
      <img src="https://placekitten.com/g/30/30" class="d-inline-block align-top" alt="BV" />
    </b-navbar-brand>
    <b-navbar-nav class="ml-auto">
    <b-nav-item href="/contact" right>Info & Contact</b-nav-item>
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
      <div class="foto-duo">
        <img src="~assets/test_portada.jpg" alt="Ron and James">
      </div>
      <div class="contacto">
        <a v-b-popover.hover="'I am popover content!'" title="Popover Title" href=""><img src="~assets/YouTube.png" alt="logo youtube"></a>
        <p>Take a look in our <a href="#">Youtube Channel</a>, maybe <a href="#">subscribe</a>.</p>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>
<style>
.fondo-home {
  background-image: url('~assets/sky.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-width: 100%;
  background-blend-mode: darken;
  min-height: 100vh;
}
.bg-light {
  background-color: transparent !important;
}
.navbar a {
  color: black;
}
.container {
  margin: 0 auto;
  min-height: 100%;
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
.foto-duo {
  width: 100%;
  text-align: center;
}
.foto-duo img {
  width: 100%;
  margin: auto;
  max-width: 600px;
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
