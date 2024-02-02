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

<style lang="scss">
@use './assets/scss/style.scss'
</style>