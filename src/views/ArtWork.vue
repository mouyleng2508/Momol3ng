<template>
  <v-container>
    <v-row id="TextLogo" align="center" justify="center">
      <p class="grey--text lighten-2 display-1 mt-4">Logo</p>
    </v-row>

    <v-row id="Logo">
      <v-col sm="6" md="4" lg="2" v-for="image in logo" :key="image">
        <v-img
          align="center"
          justify="center"
          width="200px"
          height="200px"
          :src="image"
        ></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
    <v-row id="TextComics" align="center" justify="center">
      <p class="grey--text lighten-2 display-1 mt-4">Comics</p>
    </v-row>
    <v-row id="Comics">
      <v-col
        v-for="image in comics"
        :key="image"
        class="float-left"
        lg="2"
        sm="6"
        md="4"
      >
        <v-img width="200px" height="200px" :src="image"></v-img>
      </v-col>
    </v-row>
    <v-row id="TextIllustrations" align="center" justify="center">
      <p class="grey--text lighten-2 display-1 mt-4">Illustrations</p>
    </v-row>
    <v-row id="Illustrations">
      <v-col
        v-for="image in illustrations"
        :key="image"
        cols="4"
        lg="2"
        sm="6"
        md="4"
      >
        <v-img height="200px" :src="image"></v-img>
      </v-col>
    </v-row>
    <v-row id="TextQuotes" align="center" justify="center">
      <p class="grey--text lighten-2 display-1 mt-4">Quotes</p>
    </v-row>
    <v-row id="Quotes">
      <v-col v-for="image in quotes" :key="image" lg="2" sm="6" md="4">
        <v-img width="200px" height="200px" :src="image"></v-img>
      </v-col>
    </v-row>
    <v-row id="TextDD" align="center" justify="center">
      <p class="grey--text lighten-2 display-1 mt-4">Digital Drawings</p>
    </v-row>
    <v-row id="DigitalDrawings">
      <v-col
        v-for="image in digital_drwaings"
        :key="image"
        lg="2"
        sm="6"
        md="4"
      >
        <v-img width="200px" height="200px" :src="image"></v-img>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  name: "App",
  components: {},
  data: () => ({
    logo: [
      require("../assets/Logo/AVLogo.png"),
      require("../assets/Logo/DaisyCover.png"),
      require("../assets/Logo/HonLogo.png"),
      require("../assets/Logo/CambodianCheeringPartylogo-01.png"),
      require("../assets/Logo/CambodianCheeringPartylogo-02.png"),
      require("../assets/Logo/CambodianCheeringPartyWithMask-01.png"),
      require("../assets/Logo/CambodianCheeringPartyWithoutMask-01.png"),
      require("../assets/Logo/InfiniteCompany.png"),
      require("../assets/Logo/Promofy.png"),
    ],
    comics: [
      require("../assets/Comics/all-01.png"),
      require("../assets/Comics/Unhappy-01.png"),
      require("../assets/Comics/Unhappy-02.png"),
    ],
    illustrations: [
      require("../assets/Illustrations/SchoolTrip.png"),
      require("../assets/Illustrations/Covid19.png"),
      require("../assets/Illustrations/Boutique.png"),
      require("../assets/Illustrations/momo.png"),
      require("../assets/Illustrations/CartoonMe.png"),
      require("../assets/Illustrations/ShootPhoto.png"),
    ],
    quotes: [
      require("../assets/Quotes/cactus.png"),
      require("../assets/Quotes/EnjoyLittlethings.png"),
      require("../assets/Quotes/Mask.png"),
      require("../assets/Quotes/Rainbow.png"),
      require("../assets/Quotes/Stress.png"),
    ],
    digital_drwaings: [
      require("../assets/DigitalDrawings/OctoberCalendar.png"),
      require("../assets/DigitalDrawings/peaceout.png"),
      require("../assets/DigitalDrawings/selfloved.png"),
    ],
  }),
};
</script>

<script>
export default {
  name: "App",
  components: {},
  data: () => ({
    logo: [
      require("../assets/Logo/AVLogo.png"),
      require("../assets/Logo/DaisyCover.png"),
      require("../assets/Logo/HonLogo.png"),
      require("../assets/Logo/CambodianCheeringPartylogo-01.png"),
      require("../assets/Logo/CambodianCheeringPartylogo-02.png"),
      require("../assets/Logo/CambodianCheeringPartyWithMask-01.png"),
      require("../assets/Logo/CambodianCheeringPartyWithoutMask-01.png"),
      require("../assets/Logo/InfiniteCompany.png"),
      require("../assets/Logo/Promofy.png"),
    ],
    comics: [
      require("../assets/Comics/all-01.png"),
      require("../assets/Comics/Unhappy-01.png"),
      require("../assets/Comics/Unhappy-02.png"),
    ],
    illustrations: [
      require("../assets/Illustrations/SchoolTrip.png"),
      require("../assets/Illustrations/Covid19.png"),
      require("../assets/Illustrations/Boutique.png"),
      require("../assets/Illustrations/momo.png"),
      require("../assets/Illustrations/CartoonMe.png"),
      require("../assets/Illustrations/ShootPhoto.png"),
    ],
    quotes: [
      require("../assets/Quotes/cactus.png"),
      require("../assets/Quotes/EnjoyLittlethings.png"),
      require("../assets/Quotes/Mask.png"),
      require("../assets/Quotes/Rainbow.png"),
      require("../assets/Quotes/Stress.png"),
    ],
    digital_drwaings: [
      require("../assets/DigitalDrawings/OctoberCalendar.png"),
      require("../assets/DigitalDrawings/peaceout.png"),
      require("../assets/DigitalDrawings/selfloved.png"),
    ],
  }),
};
</script>

<style scoped>
v-img {
  border-radius: 10px;
}
</style>