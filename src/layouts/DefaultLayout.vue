<template>
  <Header />
  <slot />
  <Footer />
</template>

<script>
import Header from "@/components/home/Header";
import Footer from "@/components/home/footer/Footer";
export default {
  name: "DefaultLayout",
  components: {
    Header,
    Footer,
  },
};
</script>