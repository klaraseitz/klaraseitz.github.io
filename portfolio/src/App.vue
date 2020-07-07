<template>
  <v-app>
    <PortfolioOverview></PortfolioOverview>
  </v-app>
</template>

<script>
import PortfolioOverview from "./components/PortfolioOverview";

export default {
  name: 'App',

  components: {
    PortfolioOverview
  },

  data: () => ({
    //
  }),
};
</script>
