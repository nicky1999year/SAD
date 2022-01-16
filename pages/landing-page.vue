<template>
  <v-main>
    <BannerFour />
    <FormBanner1 />
  </v-main>
</template>

<script>
export default {
  head() {
    return {
      title: "Start Building Your Website Now | Landing Page",
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
    BannerFour: () => import("@/components/shared/lp-banner/BannerFour"),
    FormBanner1: () => import("@/components/custom/form-banner/FormBanner1"),
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