<template>
  <v-app>
    <AppTopBar />
    <v-main>
      <Inicio/>
    </v-main>
  </v-app>
</template>

<script>
import Inicio from './components/Inicio.vue';
import AppTopBar from './components/shared/AppTopBar.vue';

export default {
  name: 'App',
  components: {
    Inicio,
    AppTopBar
  }
};
</script>
