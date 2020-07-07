<template>
  <div>
    <div id="contat_us" style="margin-bottom: 5rem;">
      <b-container>
        <div class="form-holder">
          <h2 class="header-text">Contact</h2>
          <form id="textarea" action="https://formspree.io/moqkkkrb" method="POST">
            <div class="form-group">
              <input class="form-control" placeholder="Enter Your Name" type="text" name="name" />
            </div>
            <div class="form-group">
              <input
                class="form-control"
                placeholder="Enter Your Email Address"
                type="email"
                name="email"
              />
            </div>
            <div class="form-group">
              <input
                class="form-control"
                placeholder="Enter Your Contact No."
                type="number"
                name="phone_number"
              />
            </div>
            <div class="form-group">
              <textarea
                placeholder="Enter Comments..."
                class="form-control"
                name="comments"
                rows="3"
              ></textarea>
            </div>
            <button class="btn btn-primary btn-gradient submit" type="submit">Submit</button>
          </form>
        </div>
      </b-container>
    </div>
    <!-- <b-navbar toggleable="lg" type="dark" variant="dark" fixed="bottom">
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>-->
    <footer class="section footer-classic context-dark bg-image" style="background: #2d3246;">
      <div class="container">
        <div class="row row-30" style="padding-top: 20px;">
          <dl class="col-md-3 contact-list">
          <h5>Contacts</h5>
          </dl>
          <dl class="col-md-3 contact-list">
            <dt>Address:</dt>
            <dd>Corp. Office: #73, Street No. 9, Guru Nanak Nagar, Patiala-147001</dd>
            <!-- <br /> -->
            <!-- <dd>Office: SCF 10-11, New Grain Market, Near HDFC Bank, Bhawanigarh</dd> -->
          </dl>
          <dl class="col-md-3 contact-list">
            <dt>email:</dt>
            <dd>
              <a href="mailto:puneetjain0001@gmail.com">puneetjain0001@gmail.com</a>
            </dd>
          </dl>
          <dl class="col-md-3 contact-list">
            <dt>phones:</dt>
            <dd>
              <a href="tel:7973591402" style="margin-right: 10px;">7973591402</a>
              <span>or</span>
              <a href="tel:9056804009" style="margin-left: 10px;">9056804009</a>
            </dd>
          </dl>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "ContactUsComponent",
  data() {
    return {};
  }
};
</script>
<style scoped>
#contat_us {
  background-image: url(../assets/contact.png);
  background-size: 100%;
}
#contat_us .form-holder {
  padding: 70px 40px;
  background-color: rgb(249, 249, 249);
  background-size: 100%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 20px;
  opacity: 0.9;
}
#contat_us form input,
#contat_us textarea,
#contat_us form select,
#contat_us .input-group {
  margin-bottom: 40px;
}
#contat_us input,
#contat_us form input,
#contat_us textarea,
#contat_us form select {
  background: rgba(0, 0, 0, 0);
  border: none;
  box-shadow: none;
  border: 1px solid rgb(204, 204, 204);
}
#contat_us .form-group textarea {
  margin-top: 10px;
  width: 100%;
  height: 158px;
  line-height: 68px;
  border-radius: 20px;
  outline: none;
  padding: 0 30px;
  font-family: "Raleway", sans-serif;
}
#contat_us .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  background: rgb(238, 238, 238);
  border: 1px solid rgb(221, 221, 221);
  border-radius: 50px;
  outline: none;
  padding: 0 30px;
  font-family: "Raleway", sans-serif;
}
.btn.btn-gradient:hover,
section.services .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}
.btn-primary:active,
.btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: rgb(56, 113, 224);
  background-image: none;
}
.btn-primary:hover {
  color: rgb(255, 255, 255);
}
.btn.btn-gradient:hover,
section.services .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}
.btn-primary:active,
.btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: rgb(56, 113, 224);
  background-image: none;
  border-color: rgb(45, 106, 222);
}
.btn-primary:hover {
  color: rgb(255, 255, 255);
  background-color: rgb(56, 113, 224);
  border-color: rgb(45, 106, 222);
}
.btn:active,
.btn.active {
  background-image: none;
}
.btn-primary.active,
.btn-primary:active,
.show > .btn-primary.dropdown-toggle {
  background-color: rgb(0, 105, 217);
  background-image: none;
  border-color: rgb(0, 98, 204);
}
.btn-primary:hover {
  color: rgb(255, 255, 255);
  background-color: rgb(0, 105, 217);
  border-color: rgb(0, 98, 204);
}
.btn.active,
.btn:active {
  background-image: none;
}
.btn:focus,
.btn:hover {
  text-decoration: none;
}
.btn-primary {
  color: rgb(255, 255, 255);
  background-color: rgb(89, 137, 229);
  border-color: rgb(89, 137, 229);
}
.btn {
  font-weight: 400;
  padding: 0.6rem 3rem;
  line-height: 1.5;
  border-radius: 50px;
}
.btn-gradient,
section.services .nav-tabs span.number {
  border: none !important;
  text-transform: uppercase;
  overflow: hidden;
  position: relative;
  z-index: 1;
  transition: all 0.3s !important;
}
.context-dark,
.bg-gray-dark,
.bg-primary {
  color: rgba(255, 255, 255, 0.8);
}
.footer-classic {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  color: white;
  text-align: center;
}
.footer-classic a,
.footer-classic a:focus,
.footer-classic a:active {
  color: #ffffff;
}
.nav-list li {
  padding-top: 5px;
  padding-bottom: 5px;
}

.nav-list li a:hover:before {
  margin-left: 0;
  opacity: 1;
  visibility: visible;
}

ul,
ol {
  list-style: none;
  padding: 0;
  margin: 0;
}

.social-inner {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  padding: 23px;
  font: 900 13px/1 "Lato", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.5);
}
.social-container .col {
  border: 1px solid rgba(255, 255, 255, 0.1);
}
.nav-list li a:before {
  content: "\f14f";
  font: 400 21px/1 "Material Design Icons";
  color: #4d6de6;
  display: inline-block;
  vertical-align: baseline;
  margin-left: -28px;
  margin-right: 7px;
  opacity: 0;
  visibility: hidden;
  transition: 0.22s ease;
}
</style>