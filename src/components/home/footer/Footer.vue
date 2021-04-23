<template>
  <footer>
    <div class="wrapper">
      <ContactSec />
      <div class="footer_links">
        <ul>
          <NavList />
        </ul>
      </div>
      <div class="copyright">
        &copy; Copyright 2021. All Rights Reserved. <span>Company Name</span>
      </div>
    </div>
  </footer>
</template>

<script>
/* import Components */
import ContactSec from "./ContactSection";
import NavList from "../nav-list/navlist";
export default {
  name: "footer",
  components: {
    ContactSec,
    NavList,
  },
};
</script>