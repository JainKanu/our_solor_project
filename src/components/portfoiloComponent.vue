<template>
  <b-container id="portfolio" style="padding: 40px;">
    <h2 class="header-text">PORTFOLIO</h2>
    <b-row class="mb-4">
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/porflolio/1.jpg')" style="width: 21rem; height: 21rem;" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/porflolio/2.jpg')" style="width: 27rem; height: 21rem;" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img
            :src="require('../assets/porflolio/3.jpg')"
             style="width: 27rem; height: 21rem;"
            alt="Image"
            class="rounded-0"
          />
        </b-card>
      </b-col>
    </b-row>
    <b-row>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/porflolio/4.jpg')" style="width: 27rem; height: 21rem;" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/porflolio/5.jpg')" style="width: 27rem; height: 21rem;" alt="Image" class="rounded-0" />
        </b-card>
      </b-col>
      <b-col cols="4">
        <b-card no-body class="overflow-hidden">
          <b-card-img :src="require('../assets/porflolio/6.jpg')"  style="width: 27rem; height: 21rem;" alt="Image" class="rounded-0" />
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