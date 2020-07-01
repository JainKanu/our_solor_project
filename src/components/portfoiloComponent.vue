<template>
  <b-container id="portfolio" style="padding: 40px;">
    <h2 class="header-text">PORTFOLIO</h2>
    <b-row class="mb-4">
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/portfoilo_01.jpg')" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/portfoilo_02.jpg')" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img
            :src="require('../assets/portfoilo_03.jpg')"
            alt="Image"
            class="rounded-0"
            style="height: 15rem;"
          />
        </b-card>
      </b-col>
    </b-row>
    <b-row>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/portfoilo_04.jpg')" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/portfoilo_05.jpg')" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/portfoilo_06.jpg')" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
export default {
  name: "PortfoiloComponent",
  data() {
    return {};
  }
};
</script>