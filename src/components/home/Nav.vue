<template>
  <div id="nav_area">
    <nav>
      <ul>
        <NavList />
      </ul>
    </nav>
  </div>
</template>

<script>
/* import Components */
import NavList from "./nav-list/navlist";

export default {
  name: "Nav",
  components: {
    NavList,
  },
};
</script>