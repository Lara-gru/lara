<template>
  <div class="travel-card">
    <h1>TravelCard</h1>
    <h3>{{ travel.name }}</h3>
  </div>
</template>

<script>
export default {
  name: 'TravelCard',
  props: {
    travel: Object,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
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
