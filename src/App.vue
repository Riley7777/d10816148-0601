<template>
  <v-app>
    <v-main class="bg">
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
<style>
@import './assets/css/style.css';
</style>