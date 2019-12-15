<template>
  <div class="container">
    <div>
      <app-header></app-header>
      <logo />
      <h1 class="title">
        diegofertr
      </h1>
      <h2 class="subtitle">
        Blog personal construído con nuxt
      </h2>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo'
import AppHeader from '~/components/AppHeader'

export default {
  components: {
    Logo,
    AppHeader
  }
}
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
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 80px;
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

.links a {
  background-color: #2196f3;
  color: white;
  text-decoration: none;
  padding: 5px;
  border-radius: 5px;
}

.links a:hover {
  background-color: #1976d2;
  color: white;
  text-decoration: underline;
  padding: 5px;
  border-radius: 5px;
}
</style>
