<template>
  <v-app dark>
    <!--v-if="$route.name!=='login'"-->
    <Header2 />
    <v-main>
      <nuxt />
    </v-main>
    <Footer2 />
  </v-app>
</template>

<script>
export default {
  head() {
    return {
      title: "NuxtJs UI kit | Free UI kit built with Vuetify",
      meta: [
        {
          hid: "description",
          name: "NuxtJs UI kit",
          content: "NuxtJs UI kit is the best way"
        }
      ]
    };
  },
  components: {
    Header2: () => import("@/layouts/sections/Header2"),
    Footer2: () => import("@/layouts/sections/Footer2")
  },
  methods: {}
};
</script>

<style></style>
