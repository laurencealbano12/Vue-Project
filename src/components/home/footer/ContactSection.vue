<template>
  <div id="contact">
    <div class="wrapper">
      <div class="contact_content">
        <div class="our_location">
          <h4>Our Location</h4>
          <p>
            Sample text. Click to select the text box. Click again or double
            click to start editing the text.
          </p>
          <iframe
            class="google-map"
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d64541848.68065448!2d-149.2396034!3d-9.1253773!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x76ed042c30f318eb%3A0x8eff14a070876cbc!2sPacific%20Ocean!5e0!3m2!1sen!2sph!4v1619146957520!5m2!1sen!2sph"
            style="border: 0"
            allowfullscreen="yes"
            loading="lazy"
          ></iframe>
        </div>
        <div class="cntct_box">
          <h4>Get in Touch with Us</h4>
          <p>
            If you’d like to learn more about what we do or have a specific
            requirement you’d like to discuss, please get in touch with us.
          </p>
          <a href="mailto:sample@gmail.com"
            ><i class="fa fa-envelope"></i>&nbsp;&nbsp;sample@gmail.com</a
          >
          <a href="tel:500-4568-421"
            ><i class="fa fa-phone"></i>&nbsp;&nbsp;500-4568-421</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactSec",
};
</script>