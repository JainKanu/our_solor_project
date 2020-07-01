<template>
  <div style="overflow-x: hidden;">
    <b-navbar fixed="top" toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="#">Solor</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#home">Home</b-nav-item>
          <b-nav-item href="#about">About</b-nav-item>
          <b-nav-item href="#how_it_works">Services</b-nav-item>
          <b-nav-item href="#portfolio">Portfolio</b-nav-item>
          <b-nav-item href="#contat_us">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div>
      <HomeCarousel />
    </div>
    <div id="page-divider"></div>
    <div style="background-color: #F9F9F9;">
      <AboutUsComponent />
    </div>
    <div id="page-divider"></div>
    <div style="background-color: #FFFFFF;">
      <HowItWorksComponent />
    </div>
    <div id="page-divider"></div>
    <div style="background-color: #F5F5F5;">
      <PortfoiloComponent />
    </div>
    <div id="page-divider"></div>
    <div>
      <ContactUsComponent />
    </div>
  </div>
</template>
<script>
import HomeCarousel from "../components/homeCarousel.vue";
import AboutUsComponent from "../components/aboutUsComponent.vue";
import HowItWorksComponent from "../components/howItWorksComponent.vue";
import PortfoiloComponent from "../components/portfoiloComponent.vue";
import ContactUsComponent from "../components/contactUsComponent.vue";
export default {
  name: "Project",
  components: {
    HomeCarousel,
    AboutUsComponent,
    HowItWorksComponent,
    PortfoiloComponent,
    ContactUsComponent
  },
  data() {
    return {};
  }
};
</script>
<style>
#page-divider {
  background-image: url(../assets/tour-bg.png);
  background-color: rgb(238, 238, 238);
  height: 100px;
  background-position: center;
  display: table;
  width: 100%;
  box-shadow: 0 1.5px 4px rgba(0, 0, 0, 0.24), 0 1.5px 6px rgba(0, 0, 0, 0.12);
}
.header-text {
  font-family: Raleway;
  font-weight: 300;
  text-transform: capitalize;
  font-size: 35px;
  color: rgb(181, 177, 174);
  letter-spacing: 2px;
  margin-bottom: 30px;
  margin-left: 5px;
  margin-top: 50px;
}
</style>
