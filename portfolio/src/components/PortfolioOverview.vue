<template>
  <div class="hello">
    <v-img height="125" src="./../assets/flowers.jpg">
      <v-row align="center" class=" pa-2 fill-height">
        <v-col align="center">
          <div class="text-h2 black--text">Klara Seitz</div>
          <div class="text-body-1 black--text">Software Developer, M.Sc.</div>
        </v-col>
      </v-row>
    </v-img>
    <ProjectTimeline></ProjectTimeline>
  </div>
</template>

<script>
import ProjectTimeline from "./ProjectTimeline";

export default {
  name: 'PortfolioOverview',
  props: {
    msg: String
  },
  components: {
    ProjectTimeline
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
