<template>
  <v-container class="home-container">
    <v-row class="profile-box d-flex flex-row">
      <v-col class="col-3">
        <v-avatar size="250">
          <img src="https://images.pexels.com/photos/2574614/pexels-photo-2574614.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
        </v-avatar>
      </v-col>
      <v-col class="col-3"><h3>Hello Bob!</h3></v-col>
    </v-row>
    <v-row class="data-box">
      <v-col class="col-8">
        <v-card height="2000px">
          <v-card-title>My Posts</v-card-title>
        </v-card>
      </v-col>
      <v-col class="col-4">
        <v-card height="2000px">
          <v-card-title>My Likes</v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'Home',
  data: () => ({
    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
  }),
};
</script>

<style scoped>
.home-container{
  min-width: 980px;
  max-width: 1100px;
}
.profile-box{
  background: linear-gradient(#4ca1af, #c4e0e5);
  height: 300px;
}
.data-box{
  background-color: white;
}
</style>
