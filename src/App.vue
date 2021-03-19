<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
      elevation="0"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />
      </div>
    </v-app-bar>

    <v-main class="router-view">
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<style>
.router-view{
  background-color: lightgrey;
}
</style>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
