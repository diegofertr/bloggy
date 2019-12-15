<template>
  <div class="container">
    <div>
      <h1 class="title">Hello, I'm {{ name }}</h1><br>
      <h3 class="subtitle">FullStack Developer more Frontend oriented</h3>
      <div>
        <p>Actualmente trabajo como desarrollador Fullstack en una entidad gubernamental de mi querida Bolivia, graduado de la Universidad Mayor de San Andrés, me dedico especialmente al desarrollo Frontend pero actualmente desarrollo backend y mobile también, particularmente me gusta ser autodidacta, aprender y mantenerme actualizado con las nuevas tecnologías.</p>
      </div>
      <div class="links">
        <nuxt-link to="/"> Ir a Home</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      name: 'Diego F. Ticona Ramos'
    }
  }
}
</script>
