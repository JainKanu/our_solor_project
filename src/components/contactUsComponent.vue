<template>
  <div id="contat_us">
    <b-container>
      <div class="form-holder">
        <h2 class="header-text">Contact</h2>
        <form id="textarea" action="https://formspree.io/mayokqjb" method="POST">
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
            <textarea placeholder="Enter Comments..." class="form-control" name="comments" rows="3"></textarea>
          </div>
          <button class="btn btn-primary btn-gradient submit" type="submit">Subscribe</button>
        </form>
      </div>
    </b-container>
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
</style>