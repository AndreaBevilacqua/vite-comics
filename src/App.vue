<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppMain from './components/AppMain.vue'

export default {
  data: () => ({
    links: [
      {
        text: 'Characters',
        url: '#',
        current: false,
      },
      {
        text: 'Comics',
        url: '#',
        current: true,
      },
      {
        text: 'Movies',
        url: '#',
        current: false,
      },
      {
        text: 'TV',
        url: '#',
        current: false,
      },
      {
        text: 'Games',
        url: '#',
        current: false,
      },
      {
        text: 'Collectibles',
        url: '#',
        current: false,
      },
      {
        text: 'Videos',
        url: '#',
        current: false,
      },
      {
        text: 'Fans',
        url: '#',
        current: false,
      },
      {
        text: 'News',
        url: '#',
        current: false,
      },
      {
        text: 'Shop',
        url: '#',
        current: false,
      },
    ]
  }),
  components: {
    AppHeader,
    AppFooter,
    AppMain
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
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