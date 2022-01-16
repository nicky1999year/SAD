<template>
  <div>
    <UiButton />
    <UiChip />
    <UiPagination />
    <UiAlert />
    <UiCard />
    <UiForm />
    <UiTable />
    <UiTooltip />
    <UiTypography />
  </div>
</template>

<script>
export default {
  name: "AllComponents",

  data() {
    return {};
  },
  components: {
    UiButton: () => import("@/components/basic/UiButton"),
    UiPagination: () => import("@/components/basic/UiPagination"),
    UiChip: () => import("@/components/basic/UiChip"),
    UiAlert: () => import("@/components/basic/UiAlert"),
    UiCard: () => import("@/components/basic/UiCard"),
    UiForm: () => import("@/components/basic/UiForm"),
    UiTable: () => import("@/components/basic/UiTable"),
    UiTooltip: () => import("@/components/basic/UiTooltip"),
    UiTypography: () => import("@/components/basic/UiTypography"),
  },
};
</script>
