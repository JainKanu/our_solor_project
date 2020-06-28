<template>
  <b-container id="how_it_works" class="text-center" style="padding-top: 50px;">
    <h2 class="header-text">How It Works</h2>
    <b-row>
      <b-col cols="12" offset="">
        <b-img :src="require('../assets/how_it_works.png')" style="height: 380px;" />
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
export default {
  name: "HowItWorksComponent",
  data() {
    return {};
  }
};
</script>