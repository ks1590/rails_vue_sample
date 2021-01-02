<template>
  <v-app id="app">
    <Header />
    <p>{{ message }}</p>
  </v-app>
</template>

<script>
import Header from "./components/Header";

export default {
  data: function() {
    return {
      message: "Hello Vue!"
    };
  },
  components: {
    Header
  }
};
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
