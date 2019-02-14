<template>
  <section class="container">
    <div class="fondo-color">
      <h1 class="title">
        Food Forest in Panama
      </h1>
      <h2 class="subtitle">
        with Ron Hunter and James Brown
      </h2>
      <div class="foto-duo">
        <img src="~assets/test_portada.jpg" alt="Responsive image">
      </div>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >
          Youtube
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          Email
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {}
}
</script>
<style>
section {
  background-image: url('~assets/sky.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-width: 100%;
  background-blend-mode: darken;
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
.links {
  padding-top: 30px;
  padding-bottom: 30px;
}
</style>
