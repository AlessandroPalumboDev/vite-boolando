<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'MyApp',

  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}

</script>

<template>
  <header>
    <AppHeader />
  </header>

  <main>
    <AppMain />
  </main>


  <footer class="background-color-black">
    <AppFooter />
  </footer>
</template>

<style></style>
