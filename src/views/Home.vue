<template>
  <Banner />
  <Middle />
  <Bottom />
</template>

<script>
// @ is an alias to /src
import Banner from "@/components/home/Banner";
import Middle from "@/components/home/Middle";
import Bottom from "@/components/home/Bottom";

export default {
  name: "Home",
  components: {
    Banner,
    Middle,
    Bottom,
  },
};
</script>
