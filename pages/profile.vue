<template>
  <div class="container profile">
    <div>
      <app-header></app-header>
      <h1 class="title">Hello, I'm {{ name }}</h1><br>
      <h3 class="subtitle">FullStack Developer more Frontend oriented</h3>
      <p>Actualmente trabajo como desarrollador Fullstack en una entidad gubernamental de mi querida Bolivia, graduado de la Universidad Mayor de San Andrés, me dedico especialmente al desarrollo Frontend pero actualmente desarrollo backend y mobile también, particularmente me gusta ser autodidacta, aprender y mantenerme actualizado con las nuevas tecnologías.</p>
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
  },
  data () {
    return {
      name: 'Diego F. Ticona Ramos'
    }
  }
}
</script>

<style>
.profile {
  margin: 2px 350px;
}
</style>
