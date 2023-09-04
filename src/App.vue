<script setup>
  import NavBar from './components/NavBar.vue';
  import Banner from './components/Banner.vue';
  import Articles from './components/Articles.vue';
  import PageFooter from './components/PageFooter.vue';
</script>

<template>
  <header>
    <NavBar/>
  </header>

  <main>
    <Banner/>
    <Articles/>
  </main>

  <footer>
    <PageFooter/>
  </footer>
</template>

<style scoped>
  
</style>
