<template>
  <!-- 
    TODO:
    https://cdn.materialdesignicons.com/4.8.95/
  -->
  <v-app dark>
    <Appbar />
    <v-content>
      <nuxt />
      <!-- TODO: https://nuxtjs.org/guide/views/ --->
    </v-content>

    <!-- 
      TODO: create a footer component and import here
     -->
  </v-app>
</template>

<script>
import Appbar from "~/components/appbar";

export default {
  components: { Appbar },
  data() {
    return {};
  }
};
</script>
