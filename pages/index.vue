<template>
  <div class="fondo-home">
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
        <p>Take a look in our <a href="#">Youtube Channel</a> and, why not, <a href="#">subscribe</a>.</p>
        <a href="/contact"><span class="info-email">Info & Contact</span></a>
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
.nav-item {
  background-color: white;
}
.navbar-nav .nav-link {
  padding-right: 0.5rem;
  padding-left: 0.5rem;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
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
  padding-top: 40px;
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
  max-width: 550px;
}
.contacto {
  width: 100%;
  padding: 0 0 40px;
}
.contacto img {
  width: 110px;
  padding: 20px 0;
}
.contacto a {
  color: #d52423;
}
.contacto span {
  color: #212529;
}
@media (max-width: 750px) {
  .title {
    font-size: 40px;
    padding-top: 50px;
  }
  .subtitle {
    font-size: 16px;
  }
}
</style>
