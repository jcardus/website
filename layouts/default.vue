<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">
        <img src="/fleetmap.png" style="width: 70px" alt="">
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse" />
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto" />
      </b-collapse>
    </b-navbar>
    <Nuxt />
  </div>
</template>

<script>
export default {
  name: 'DefaultPage'
}
</script>

<style scoped>

</style>
