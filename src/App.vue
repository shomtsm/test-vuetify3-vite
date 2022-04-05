<template>
  <v-app>
    <v-main>
      <HelloWorld />

      <div class="d-flex justify-center">
        <v-icon>mdi-home</v-icon>
        <v-icon>mdi-account</v-icon>
      </div>
      
      <FormTest />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import FormTest from "./components/FormTest.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    FormTest,
  },

  data: () => ({
    //
  }),
};
</script>
