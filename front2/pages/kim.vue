<template>
  <section class="container">
    <h1>Demo examples of vue-chartjs</h1>
    <div class="column">
      <h3>Line Chart</h3>
      <chart></chart>
    </div>
  </section>
</template>
 
<script>
import Chart from "@/component/Chart.js";

export default {
  name: "VueChartJS",
  components: {
    Chart,
  },
};
</script>
 
<style scoped>
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