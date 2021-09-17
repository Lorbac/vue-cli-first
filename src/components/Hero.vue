<template>
  <div class="hero">
    <img src="https://www.beprime.it/wp-content/uploads/2018/08/come-risolvere-un-errore-404-900x400-780x347.jpg" alt="">
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .hero img {
        width: 50%;
    }
</style>