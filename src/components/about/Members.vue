<template>
  <div class="members-content">
    <div
      class="member-box"
      v-for="data in myJson"
      :key="data.id"
      :data-id="data.id"
    >
      <img :src="data.image_url" />
      <h4>
        {{ data.name }}
        <span>{{ data.position }}</span>
      </h4>
      <p>{{ data.info }}</p>
      <a :href="data.link_to_url" target="_blank">{{ data.link_to_profile }}</a>
    </div>
  </div>
</template>

<script>
import json from "@/assets/js/data/members.json"; // import json data from members.json

export default {
  name: "Members",
  data() {
    return {
      myJson: json,
    };
  },
};
</script>