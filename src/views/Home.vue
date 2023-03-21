<template>
  <v-app
    id="inspire"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <v-container>
      <v-row>
        <v-col class="mb-3" cols="12" sm="12">
          <Xrp1 />
          <!-- <v-row>
            <v-col cols="12" sm="4">
              <Overview />
            </v-col>
            <v-col cols="12" sm="8">
              <Money />
            </v-col>
            <v-col cols="12" sm="12">
              <Payment />
            </v-col>
          </v-row> -->
        </v-col>
        <v-col cols="12" sm="12">
          <Xrp2 />
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src
// import SideBar from "../components/SideBar";
// import Navbar from "../components/Navbar";
import Xrp1 from "../components/filldata/Xrp1";
import Xrp2 from "../components/filldata/Xrp2";
// import Overview from "../components/Overview";
// import Overview from "../components/Overview";
// import Money from "../components/Money";
// import Payment from "../components/Payment";
// import Card from "../components/Card";
export default {
  data: () => ({}),
  components: {
    Xrp1,
    Xrp2,
    // Navbar,
    // Overview,
    // Money,
    // // Payment,
    // Card,
  },
};
</script>
<style>
.v-btn.withoutupercase {
  text-transform: none !important;
}
.v-btn:not(.v-btn--round).v-size--small {
  min-width: 30px !important;
  padding: 0 5px !important;
}
</style>
