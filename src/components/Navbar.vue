<template>
  <nav>
    <!-- <v-layout justify-center>
      <v-img
        src="../assets/home.gif"
        alt=""
        class="py-5"
        contain
        height="280px"
        width="350px"
      >
      </v-img>
    </v-layout> -->
    <v-layout mt-4 column align-center>
      <v-flex>
        <v-avatar size="100">
          <img src="../assets/peaceout.png" />
        </v-avatar>
      </v-flex>
    </v-layout>

    <v-toolbar app fixed flat dense class="px-4">
      <v-spacer></v-spacer>
      <v-card
        class="hidden-sm-and-down"
        align="center"
        flat
        justify="space-around"
      >
        <v-btn text to="/">HOME</v-btn> |
        <v-btn text to="/about">ABOUT</v-btn> |
        <v-btn text to="/art_works">ART WORKS</v-btn> |
        <v-btn text to="/experiences">EXPERIENCES</v-btn>
      </v-card>
      <v-spacer></v-spacer>
      
    </v-toolbar>
  </nav>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>
