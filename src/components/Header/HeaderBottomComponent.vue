<template>
  <!-- Header Bottom Start -->
  <div class="container-fluid header_bottom_main">
    <div class="container">
      <div class="row py-2">
        <div class="col-md-6 col-12 p-0">
          <div class="header_bottom_left">
            <img
              src="./../../assets/images/logo.png"
              alt=""
              class="img-fluid"
            />
          </div>
        </div>
        <div class="col-md-6 col-12 p-0">
          <div class="header_bottom_right">
            <button><i class="fa fa-search" aria-hidden="true"></i></button>
            <button>Quick Contact</button>
            <button>Clearance Form</button>
            <button>Quick Info</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Menu Line Start -->
  <div class="header_menu_top"></div>
  <!-- Menu Line End -->

  <!-- Header Bottom End -->
</template>

<script>
export default {
  name: "HeaderBottomComponent",
  props: {
    msg: String,
  },
};
</script>

<style>
/* Header Bottom Start */

.header_bottom_right {
  padding: 20px 0px !important;
  display: table;
  float: right;
}

.header_bottom_right button {
  background-color: #31aed3;
  border-radius: 4px;
  padding: 05px 15px !important;
  border: none;
  outline: none;
  font-family: "Rubik", sans-serif;
  font-size: 14px;
  font-weight: 500;
  line-height: 17px;
  letter-spacing: 0em;
  text-align: left;
  color: #ffffff;
  margin-left: 10px !important;
}

@media only screen and (max-width: 600px) {
  .header_bottom_right {
    padding: 20px 0px !important;
    display: block;
    float: none;
  }
  .header_bottom_right button {
    background-color: #31aed3;
    border-radius: 4px;
    padding: 5px 5px !important;
    border: none;
    outline: none;
    font-family: "Rubik", sans-serif;
    font-size: 14px;
    font-weight: 500;
    line-height: 17px;
    letter-spacing: 0em;
    text-align: left;
    color: #ffffff;
    margin-left: 10px !important;
  }
}

/* Header Bottom End */

/* Menu Line Start */

.header_menu_top {
    height: 20px;
    background-color: #72006D;
}


/* Menu Line End */
</style>
