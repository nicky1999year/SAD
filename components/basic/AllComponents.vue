<template>
  <div>
    <AboutParagraph />
    <Vision />
    <Mission />
  </div>
</template>

<script>
export default {
  name: "AllComponents",

  data() {
    return {};
  },
  components: {
    AboutParagraph: () => import("@/components/basic/aboutParagraph"),
    Vision: () => import("@/components/basic/Vision"),
    Mission: () => import("@/components/basic/Mission"),
  },
};
</script>
