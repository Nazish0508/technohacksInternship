<template>
  <v-app>
    <v-app-bar app color="deep-purple" dark>
      <div class="d-flex slign-center"></div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
