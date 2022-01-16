<template>
  <div>
    <!-- -----------------------------------------------
    Banner
    ----------------------------------------------- -->
    <Banner />
    <!-- -----------------------------------------------
    ./ Banner
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    All Components
    ----------------------------------------------- -->
    <AllCustomComponents />
    <!-- -----------------------------------------------
    ./ All Components
    ----------------------------------------------- -->
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Create Restaurant Websites Within 30 Minutes | Solutech",
      meta: [
        {
          hid: "description",
          name: "Next Ui Kit",
          content: "Next Ui Kit is the best way",
        },
      ],
    };
  },

  data() {
    return {};
  },
  components: {
    Banner: () => import("@/components/shared/lp-banner/Banner"),
    AllCustomComponents: () =>
      import("@/components/custom/AllCustomComponents"),
  },
};
</script>
