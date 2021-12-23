<template>
  <div class="textStart">
    <h3>{{ message1 }}</h3>
    <h4>{{ message2 }}</h4>
  </div>
</template>

<script>
export default {
  name: "Text",
  props: {
    message1: String,
    message2: String,
  },
};
</script>

<style scoped>
h3 {
  color: #904B90;
}
h4 {
  color: #9B92CA;
}
</style>