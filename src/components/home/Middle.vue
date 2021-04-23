<template>
  <div id="middle">
    <div class="wrapper">
      <div class="mid_content">
        <h5>{{ mid_title }}</h5>
        <div class="mid_mainbox">
          <div class="midbox" v-for="service in services" :key="service.title">
            <h4>{{ service.title }}</h4>
            <p>{{ service.text }}</p>
            <a href="/services"
              ><small
                ><svg
                  version="1.1"
                  width="12px"
                  height="12px"
                  viewBox="0 0 9.1 5.6"
                >
                  <polygon
                    points="1.1,0 4.5,3.5 8,0.1 9.1,1.2 4.5,5.6 0,1 "
                  ></polygon></svg></small
            ></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Middle",
  data() {
    return {
      mid_title: "Our Services We Offered",
      services: [
        {
          title: "Web Optimization",
          text:
            "This is a dummy text to display in view. This is for the content purposes only. This will be replaced by individual contents of this section ones ready.",
        },
        {
          title: "Web Design & Development",
          text:
            "This is a dummy text to display in view. This is for the content purposes only. This will be replaced by individual contents of this section ones ready.",
        },
        {
          title: "Web Modifications",
          text:
            "This is a dummy text to display in view. This is for the content purposes only. This will be replaced by individual contents of this section ones ready.",
        },
        {
          title: "SEO Optimization",
          text:
            "This is a dummy text to display in view. This is for the content purposes only. This will be replaced by individual contents of this section ones ready.",
        },
      ],
    };
  },
};
</script>