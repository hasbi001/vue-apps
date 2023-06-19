<template>
  <v-app>
    <v-main>
      <IndexHome/>
    </v-main>
  </v-app>
</template>

<script>
import IndexHome from './components/IndexHome';

export default {
  name: 'App',

  components: {
    IndexHome,
  },

  data: () => ({
    //
  }),
};
</script>
