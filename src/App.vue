<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
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
    AppMain,
    AppTools,
    AppFooter,
  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppTools></AppTools>
  <AppFooter></AppFooter>
</template>

<style scoped></style>
