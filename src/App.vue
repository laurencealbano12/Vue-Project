<template>
  <default-layout>
    <router-view />
  </default-layout>
</template>

<script>
import DefaultLayout from "./layouts/DefaultLayout";
export default {
  name: "App",
  components: {
    DefaultLayout,
  },
};
</script>