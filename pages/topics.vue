<template>
  <v-main>
    <BannerThree />
    <Pricing />
  </v-main>
</template>

<script>
export default {
  layout: "coming-soon",
  props: {
    error: {
      type: Object,
      default: null
    }
  },
  components: {
    BannerThree: () => import("@/components/shared/lp-banner/BannerThree"),
    Pricing: () => import("@/components/custom/pricing/Pricing")
  },
  data() {
    return {
      pageNotFound: "404 Not Found",
      otherError: "An error occurred"
    };
  }
};
</script>

<style scoped>
h1 {
  font-size: 20px;
}
</style>
