<template>
  <section id="services" class="services">
    <div class="container">
      <div class="row d-flex justify-content-center">
        <div class="col-lg-8 text-center">
          <h2 class="header-text">Learn About Solar</h2>
          <div class="services-mockup">
            <div id="nav-tabContent" class="tab-content">
              <div v-if="firstTab" style="padding: 30px;">
                <b-img :src="require('../assets/servcies/2.png')" class="img-fluid" />
              </div>
              <div v-if="secondTab" style="padding: 30px;">
                <b-img :src="require('../assets/servcies/3.png')" class="img-fluid" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        id="myTab"
        role="tablist"
        class="nav nav-tabs"
        style="justify-content: center;height: 10rem;"
      >
        <div class="row" style="margin-left: 55px;">
          <div class="col-md-6">
            <a style="height: 10rem;" @click="showFirstTab" class="nav-item nav-link active">
              <span class="number">1</span>
              <div class="uk-card uk-card-body" style="margin-top: 50px;">
                <h3 class="uk-card-title">What Is Solar Power</h3>
              </div>
            </a>
          </div>
          <div class="col-md-6">
            <a style="height: 10rem;" @click="showSecondTab" class="nav-item nav-link">
              <span class="number">2</span>
              <div class="uk-card uk-card-body" style="margin-top: 50px;">
                <h3 class="uk-card-title">Why Use Solar Power</h3>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "HowItWorksComponent",
  data() {
    return {
      firstTab: true,
      secondTab: false
    };
  },
  methods: {
    showFirstTab() {
      this.firstTab = true;
      this.secondTab = false;
    },
    showSecondTab() {
      this.secondTab = true;
      this.firstTab = false;
    }
  }
};
</script>
<style>
section {
  padding: 50px 0;
  overflow: hidden;
  display: block;
}
.services-mockup {
  border-top: 50px solid rgb(247, 247, 247);
  position: relative;
  border-radius: 3px 3px 0 0;
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}
.services-mockup:before {
  display: block;
  position: absolute;
  content: "";
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: rgb(255, 68, 68);
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}
.services-mockup > * {
  display: block;
}
.img-fluid {
  max-width: 100%;
  height: auto;
}
section.services .nav-tabs {
  margin-top: 80px;
  border: none;
}
section.services .nav-tabs b-button.active {
  transform: translateY(-20px);
}
section.services .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: rgb(255, 255, 255);
  text-align: center;
  border-radius: 50%;
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}
section.services .nav-tabs span.number {
  background-color: rgb(89, 137, 229);
  background-image: linear-gradient(
    to right,
    rgb(89, 137, 229),
    rgb(55, 207, 220)
  );
  border: none !important;
  text-transform: uppercase;
  /* color: rgb(255, 255, 255); */
  overflow: hidden;
  /* position: relative; */
  z-index: 1;
  transition: all 0.3s !important;
}
</style>