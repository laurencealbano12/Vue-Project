<template>
  <div id="banner">
    <div class="wrapper">
      <div class="bnr_content">
        <div class="slogan">
          <h4>
            {{ title }} <span>{{ span_title }}</span>
          </h4>
          <p>{{ text }}</p>
          <router-link to="/contact-us">{{ button }}</router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
  data() {
    return {
      title: "Delivering High Quality",
      span_title: "Web Deveoplment Services",
      text:
        "We can give you an excellent skills and knowledges that will help in achieving your dream website.",
      button: "Contact Us",
    };
  },
};
</script>