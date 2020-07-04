<template>
  <div id="home" style="overflow-y: hidden;">
    <!-- <div style="padding-top: 7rem;">
      <b-container class="text-left">
        <b-row class="d-flex">
          <b-col cols="6" style="transform: translateY(100px);">
            <h2>Creative Designer</h2>
            <p>Design trends are influenced by the media, technology, the fashion industry and, ultimately, usability.</p>
          </b-col>
          <b-col cols="6">
            <b-img :src="require('../assets/home_lap.png')" style="height: 380px;" />
          </b-col>
        </b-row>
      </b-container>
    </div> -->
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="3000"
      controls
      indicators
      background="#ababab"
      :img-width="1024"
      :img-height="480"
      style="text-shadow: 1px 1px 2px #333; height: 100vh;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide :img-src="require('../assets/carouselImages/so5.jpg')"></b-carousel-slide>
      <b-carousel-slide :img-src="require('../assets/carouselImages/agwp2-1024x768.jpg')"></b-carousel-slide>
      <b-carousel-slide :img-src="require('../assets/carouselImages/agriculture.jpg')"></b-carousel-slide>
      <b-carousel-slide :img-src="require('../assets/carouselImages/solar_2.jpg')"></b-carousel-slide>
    </b-carousel>
  </div>
</template>
<script>
export default {
  name: "HomeCarousel",
  data() {
    return {
      slide: 0,
      sliding: null
    };
  },
  methods: {
    onSlideStart() {
      this.sliding = true;
    },
    onSlideEnd() {
      this.sliding = false;
    }
  }
};
</script>
<style>
#home {
  color: rgb(255, 255, 255);
  background-image: linear-gradient(
    to right,
    rgb(89, 137, 229),
    rgb(55, 207, 220)
  );
}
</style>