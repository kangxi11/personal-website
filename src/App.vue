<template>
  <v-app
    id="main"
    class="black"
  >
    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<style lang="postcss" scoped>
.v-application {
  background-color: white;
  font-family: $body-font-family, sans-serif !important;
}
</style>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
