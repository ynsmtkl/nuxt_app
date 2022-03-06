<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand :to="'/'">NavBar</b-navbar-brand>

      <b-navbar-nav>
        <b-nav-item :to="'/brands'">Brands</b-nav-item>
        <b-nav-item :to="'/statistics'">Statistics</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
      <Nuxt/>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>
