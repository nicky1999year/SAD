<template>
  <v-main>
    <BannerFour />
    <FormBanner3 />
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
    FormBanner3: () => import("@/components/custom/form-banner/FormBanner3"),
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