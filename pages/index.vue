<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        nuxt-ssr-redirection-loop
      </h1>
      <h2>See <a href="https://github.com/nuxt/nuxt.js/issues/8116" target="_blank">https://github.com/nuxt/nuxt.js/issues/8116</a></h2>
      <div class="links">
        <a
          href="/redirection/no-loop"
          class="button--green"
        >
          Redirect with no loop
        </a>
        <a
          href="/redirection/with loop"
          class="button--red"
        >
          Redirect with loop
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
