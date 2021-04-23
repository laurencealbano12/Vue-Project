
<template>
  <header>
    <div class="wrapper">
      <div class="logo">
        <a href="#"><img alt="Vue logo" src="../../assets/logo.png" /></a>
      </div>
      <Navigation />
    </div>
  </header>
  <div class="clearfix"></div>
</template>

<script>
/* Load Components */
import Navigation from "./Nav";

export default {
  name: "Header",
  components: {
    Navigation,
  },
};
</script>