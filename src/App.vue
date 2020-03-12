<template>
  <v-app>
    <v-content>
      <MainVue/>
    </v-content>
  </v-app>
</template>

<script>
import MainVue from './components/MainVue';

export default {
  name: 'App',

  components: {
    MainVue
  },

  data: () => ({
  }),
};
</script>
