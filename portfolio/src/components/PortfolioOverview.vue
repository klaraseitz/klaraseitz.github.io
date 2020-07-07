<template>
  <div class="hello">
    <p>
      I'm a Software Developer with a Masters Degree from HPI, Potsdam, Germany (September 2020).
    </p>
    <ProjectCard></ProjectCard>
  </div>
</template>

<script>
import ProjectCard from "./ProjectCard";

export default {
  name: 'PortfolioOverview',
  props: {
    msg: String
  },
  components: {
    ProjectCard
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
