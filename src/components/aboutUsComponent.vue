<template>
  <b-container id="about" class="text-center" style="padding-top: 50px;height: 100vh;">
    <h2 class="header-text">About Us</h2>
    <b-row>
      <b-col cols="6">
        <b-img :src="require('../assets/about_img.png')" style="height: 380px;" />
      </b-col>
      <b-col cols="6">
        <div class="bg-white" style="padding-top: 50px; height: 250px; transform: translateY(50px);">
          <h4>
            <b>Who We Are</b>
          </h4>
          <p
            class="text-muted"
          >We continuosly seek between design and technology. For over a decade, we've helped businesses to craft honest, emotional experiences through strategy, brand development, graphic design, web design. Our team hand picked to provide the right balance of skills to work.</p>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
export default {
  name: "AboutUsComponent",
  data() {
    return {};
  }
};
</script>