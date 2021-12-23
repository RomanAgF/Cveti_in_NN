<template>
  <img
    alt="Vue logo"
    src="https://259506.selcdn.ru/site499894/0e52ca29-46ee-4b7a-ad68-2f873622ee08/0e52ca29-46ee-4b7a-ad68-2f873622ee08-114209.jpeg"
  />
  <Text message1="Цветы" />
  <Text message2="Раскрась свой мир!" />
  <Links nameLink1="Купить рассаду цветов" />
  <Links nameLink2="Подробнее о нас" />
</template>

<script>
import Links from "./components/Links.vue";
import Text from "./components/Text.vue";

export default {
  name: "App",
  components: {
    Links: Links,
    Text: Text,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
