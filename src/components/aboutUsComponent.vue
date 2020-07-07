<template>
  <b-container id="about" class="text-center" style="padding-top: 50px;height: 100vh;">
    <h2 class="header-text">About Us</h2>
    <b-row>
      <b-col cols="6">
        <b-img :src="require('../assets/about_us/about_us_img.jpg')" style="width: 30rem;height: 22rem;" />
      </b-col>
      <b-col cols="6">
        <div class="bg-white" style="padding: 25px 20px 0 20px;height: 300px;transform: translateY(35px);">
          <h4>
            <b>Who We Are</b>
          </h4>
          <p
            class="text-muted"
          >Umeed Solar is specializes in diversified range of Solar Energy based products. We believe solar power industry is a fast growing business with a bright sustainable future. There are multiple reasons why people are switching to renewable sources of energy which will play a key role in shaping up our future society. With a vision of ‘Energy for everyone’ , Umeed Solar is providing high performance solar products for people all across the Punjab. Our mission is to ensure rapid and extensive penetration of the solar energy industry’s footprint in Punjab by building strategic partnerships with all stakeholders.</p>
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