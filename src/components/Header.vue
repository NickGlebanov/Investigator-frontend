<template>
  <!-- header -->
  <header>
    <va-navbar color="#7FFFD4FF">
      <template #left>
        <va-navbar-item><a>Logo</a></va-navbar-item>
      </template>
      <template #right>
        <va-navbar-item>Right</va-navbar-item>
      </template>
    </va-navbar>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style lang="stylus" scoped>
.va-navbar {
  border-radius 20px

}
</style>
