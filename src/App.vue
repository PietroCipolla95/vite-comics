<script>

import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import AppTools from './components/AppTools.vue';
import AppFooter from './components/AppFooter.vue'

export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppJumbotron,
    AppTools,
    AppFooter,
  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppJumbotron></AppJumbotron>
  <AppTools></AppTools>
  <AppFooter></AppFooter>
</template>

<style scoped></style>
