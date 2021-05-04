<template>
  <other-page-layout>
    <h2>This is About Page</h2>
    <p>
      This is a dummy text to display in view. This is for the content purposes
      only. This will be replaced by individual contents of this section ones
      ready.
    </p>

    <h2>Meet our members:</h2>

    <Members />
  </other-page-layout>
</template>

<script>
import OtherPageLayout from "@/layouts/OtherPageLayout";
import Members from "@/components/about/Members";

export default {
  name: "About",
  components: {
    OtherPageLayout,
    Members,
  },
};
</script>