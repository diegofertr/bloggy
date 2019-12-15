<template>
  <div class="header__main">
    <div class="header__main-img">
      <img src="../assets/logo-main.png" alt="logo-main">
    </div>
    <nav class="header__main-nav">
      <nuxt-link to="/">Home</nuxt-link>
      <nuxt-link to="/projects">Proyectos</nuxt-link>
      <nuxt-link to="/profile">Sobre mí</nuxt-link>
    </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.header__main {
  /* width: 100vw; */
  display: flex;
  justify-content: space-between;
  align-items: center;
  /* background: red; */
  margin-bottom: 20px;
}

.header__main-img img{
  border-radius: 8px;
  width: 200px;
}

.header__main-nav {
  display: flex;
  justify-content: space-evenly;
}

.header__main-nav a {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  text-decoration: none;
  margin: 0 5px;
  font-size: 1.2rem;
  color: #f9a825;
  padding: 5px;
}

.header__main-nav a:hover {
  text-decoration: underline;
  margin: 0 5px;
  font-size: 1.2rem;
  color: #263238;
  background: #fafafa;
  border-radius: 5px;
}
</style>
