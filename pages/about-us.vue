<template>
  <div>
    <BannerTwo />
    <AllComponents />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Find Out More About Our Company | About Us",
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
    BannerTwo: () => import("@/components/shared/lp-banner/BannerTwo"),
    AllComponents: () => import("@/components/basic/AllComponents"),
  },
};
</script>
