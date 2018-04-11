<template>
  <div class="header">
    <h1>{{ msg }}</h1>
    <h2>页头</h2>
  </div>
</template>

<script>
export default {
  name: 'header-com',
  data () {
    return {
      msg: 'Welcome to my blog'
    }
  }
}
</script>

<style scoped>

</style>