<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppTools from './components/AppTools.vue';

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
  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppTools></AppTools>
</template>

<style scoped></style>
