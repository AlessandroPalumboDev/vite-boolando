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


  <footer>
    <AppFooter />
  </footer>
</template>

<style lang="scss" scoped>
header {
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  width: 100%;
  background-color: rgb(235, 122, 29);
  padding: 10px 20px;
}

main {
  margin: auto;
  margin-top: 65px;
  margin-bottom: 80px;
}

footer {
  position: fixed;
  z-index: 1;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 20px;
  background-color: black;

}
</style>
