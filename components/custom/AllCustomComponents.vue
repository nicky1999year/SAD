<template>
  <div>
    <!-- -----------------------------------------------
    Features
    ----------------------------------------------- -->
    <FeatureText />
    <Feature1 />
    <Feature2 />
    <Feature3 />
    <!-- -----------------------------------------------
    ./ Features
    ----------------------------------------------- -->    
    <!-- -----------------------------------------------
    Banner
    ----------------------------------------------- -->
    <Banner1 />
    <!-- -----------------------------------------------
    ./ Banner
    ----------------------------------------------- -->

    <!-- -----------------------------------------------
    Team
    ----------------------------------------------- -->
    <Team />
    <!-- -----------------------------------------------
    ./ Team
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    Testimonial
    ----------------------------------------------- -->
    <TestimonialText />
    <Testimonial />
    <!-- -----------------------------------------------
    ./ Testimonial
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    C2a
    ----------------------------------------------- -->
    <C2aText />
    <C2a2 />
    <!-- -----------------------------------------------
    ./ C2a
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    Contact Text
    ----------------------------------------------- -->
    <ContactText />
    <Contact />
    <!-- -----------------------------------------------
    ./ Contact Text
    ----------------------------------------------- -->
  </div>
</template>

<script>
export default {
  name: "AllCustomComponents",

  data() {
    return {};
  },
  components: {
    FeatureText: () => import("@/components/custom/features/FeatureText"),
    ContactText: () => import("@/components/custom/contact/ContactText"),
    TestimonialText: () =>
      import("@/components/custom/testimonial/TestimonialText"),
    C2aText: () => import("@/components/custom/c2a/C2aText"),
    FormBannerText: () =>
      import("@/components/custom/form-banner/FormBannerText"),
    Banner1: () => import("@/components/custom/banner/Banner1"),
    Feature1: () => import("@/components/custom/features/Feature1"),
    Feature2: () => import("@/components/custom/features/Feature2"),
    Feature3: () => import("@/components/custom/features/Feature3"),
    Team: () => import("@/components/custom/team/Team"),
    Testimonial: () => import("@/components/custom/testimonial/Testimonial"),
    C2a2: () => import("@/components/custom/c2a/C2a2"),
    Contact: () => import("@/components/custom/contact/Contact"),
  },
};
</script>
