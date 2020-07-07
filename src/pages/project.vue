<template>
  <div style="overflow-x: hidden;overflow-y: hidden;">
    <div id="header" class>
      <div class="header_left vertical_middle">
        <img src="../assets/logo/title_logo.png" />
      </div>
      <div class="right-part-nav">
        <div id="cssmenu">
          <ul id="MainMenu" class="menu" style="padding-top: 10px;">
            <li
              id="nav-menu-item-2543"
              class="first-level menu-item-depth-0 menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children has-sub"
            >
              <div class="transition hovercolor"></div>
              <a href="#home" class="menu-link main-menu-link">Home</a>
            </li>
            <li
              id="nav-menu-item-2503"
              class="first-level menu-item-depth-0 menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children has-sub"
            >
              <div class="transition hovercolor"></div>
              <a href="#about" class="menu-link main-menu-link">About Us</a>
            </li>
            <li
              id="nav-menu-item-2504"
              class="first-level menu-item-depth-0 menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children has-sub"
            >
              <div class="transition hovercolor"></div>
              <a href="#services" class="menu-link main-menu-link">Services</a>
            </li>
            <li
              id="nav-menu-item-2961"
              class="first-level menu-item-depth-0 menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children has-sub"
            >
              <div class="transition hovercolor"></div>
              <a href="#portfolio" class="menu-link main-menu-link">Portfolio</a>
            </li>
            <li
              id="nav-menu-item-2961"
              class="first-level menu-item-depth-0 menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children has-sub"
            >
              <div class="transition hovercolor"></div>
              <a href="#contat_us" class="menu-link main-menu-link">Contact</a>
            </li>
          </ul>
        </div>
        <div class="header_right">
          <ul>
            <li class="vertical_middle">
              <img src="../assets/logo/main_logo.jpg" />
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- <b-navbar fixed="top" toggleable="lg" type="light" variant="faded">
      <b-navbar-brand>
        <b-img :src="require(`../assets/logo/title_logo.png`)" alt="logo" />
      </b-navbar-brand>
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
    </b-navbar>-->
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
#header {
  position: fixed;
  height: 90px;
  display: block;
  width: 100%;
  background: rgb(255, 255, 255);
  z-index: 9;
  text-align: center;
  padding: 0;
  box-shadow: 0 1px 9px -1px rgba(0, 0, 0, 0.5);
  top: 0;
}
.vertical_middle,
.vertical_middle:before {
  height: 100%;
  vertical-align: middle;
}
.header_left {
  transform: translateY(25px);
  float: left;
  margin-left: 28px;
  position: relative;
}
.right-part-nav {
  display: inline-block;
}
.header_right,
.right-part-nav {
  float: right;
  height: 100%;
}
.header_right ul {
  height: 100%;
}
ul {
  list-style-type: none;
}
.header_right ul li {
  float: left;
  border-left: 1px solid rgb(204, 204, 204);
  height: 100%;
  padding: 0 15px;
}
.vertical_middle,
.vertical_middle:before {
  vertical-align: middle;
}
.header_right ul li:first-child {
  width: 130px;
}
.vertical_middle > * {
  display: inline-block;
  vertical-align: middle;
}
.header_right .vertical_middle img {
  height: 80px;
  width: 100px;
  padding-top: 10px;
}
#cssmenu {
  font-family: "ubunturegular";
  background: 0 0;
  display: inline-block;
  float: left;
  height: 100%;
}
#cssmenu,
#cssmenu #menu-button,
#cssmenu ul,
#cssmenu ul li,
#cssmenu ul li a {
  margin: 0;
  border: 0;
  list-style: none;
  line-height: 1;
  position: relative;
  box-sizing: border-box;
}
.vertical_middle > * {
  display: inline-block;
  vertical-align: middle;
}
#cssmenu > ul > li:first-child,
#cssmenu > ul > li:nth-child(2) {
  background: 0 0;
  margin-left: 0;
}
#cssmenu > ul > li > .hovercolor {
  position: absolute;
  width: 100%;
  height: 76px;
  left: 0;
  top: 0;
  background: rgb(14, 81, 157);
  opacity: 0;
}
.transition {
  transition: all 0.35s ease;
}
#cssmenu > ul > li {
  float: left;
  position: relative;
}
#cssmenu > ul > li.has-sub > a {
  padding: 31px 0;
  text-transform: uppercase;
  margin-left: 15px;
  margin-right: 15px;
}
#cssmenu > ul > li > a {
  display: inline-block;
  font-size: 14px;
  color: rgb(0, 0, 0);
  text-decoration: none;
  margin: 0 15px;
}
:focus,
a,
img,
input {
  outline: 0;
}
#cssmenu:after,
#cssmenu > ul:after {
  content: ".";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}
</style>
