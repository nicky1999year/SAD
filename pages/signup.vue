<template>
  <v-main>
    <Banner />
  </v-main>
</template>

<script>
export default {
  head() {
    return {
      title: "Sign Up For Free Todaay | Sign Up",
      meta: [
        {
          hid: "description",
          name: "Next Ui Kit",
          content: "Next Ui Kit is the best way",
        },
      ],
    };
  },
  components: {
    Banner: () => import("@/components/shared/lp-banner/BannerComingSoon")
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
