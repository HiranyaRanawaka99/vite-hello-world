<script>
  import AppHero from './components/AppHero.vue';
  export default {
    data() {
      return {
        title: 'La mia prima App con vite',
      }
    },

    components : { AppHero }
  }
</script>


<template>
  <div class="container">
    <h1> {{ title }}</h1>

    <AppHero></AppHero>
  </div>
</template>

<style lang="scss" scoped>
  h1 {
    text-align: center;
    font-size: 3rem;
  }
</style>