<script>
import AppHeader from './components/AppHeader.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBot from './components/AppFooterBot.vue';
import AppMain from './components/AppMain.vue';

export default {
  components: {
    AppHeader,
    AppFooterTop,
    AppFooterBot,
    AppMain
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooterTop />
  <AppFooterBot />
</template>

<style>
/* Reset */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */

body {
  max-height: 100vh;
  background-color: lightgray;
  font-family: "Open Sans", sans-serif;
}

img {
  max-width: 100%;
}

a {
  text-decoration: none;
}

/* Utils */

.container {
  margin: 0 auto;
  max-width: 1200px;
}

ul li {
  text-decoration: none;
  list-style-type: none;
}
</style>