<template>
  <div class="hello">
    <a href="#">{{ nameLink1 }}</a>
    <a href="#">{{ nameLink2 }}</a>
  </div>
</template>

<script>
export default {
  name: "Links",
  props: {
    msg: String,
    nameLink1: String,
    nameLink2: String,
    urlLnk: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  display: inline;
  padding: 5px;
}
a {
  border: 0.1px groove;
  padding: 5px;
  background-color: #C44569;
}
</style>
