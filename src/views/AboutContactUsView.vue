<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <div class="about_contact_us_main">
      <div class="container">
          <div class="row">
              <h1>Location Map</h1>
          </div>

          <div class="row">
              <div class="about_contact_us_main_map">
                  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3650.8938650862287!2d90.41303991429767!3d23.786793493303485!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c79753d524b3%3A0x370d933bad42f295!2sFlyte%20Solutions%20%7C%20Custom%20Software%20Development%20Company!5e0!3m2!1sen!2sbd!4v1654509784169!5m2!1sen!2sbd" width="800" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              </div>
          </div>

          <div class="row">
              <div class="about_contact_us_main_contact">
                  <ul>
                      <h5>International Islamic University Chittagong</h5>
                      <li>Kumira, Chittagong-4318, Bangladesh</li>
                      <li>IP Tel.: +8809613230505</li>
                      <li>Fax.: +8802334461930</li>
                      <li>Email: info@iiuc.ac.bd</li>
                  </ul>
                  <ul>
                      <h5>International Islamic University Chittagong</h5>
                      <li>Kumira, Chittagong-4318, Bangladesh</li>
                      <li>IP Tel.: +8809613230505</li>
                      <li>Fax.: +8802334461930</li>
                      <li>Email: info@iiuc.ac.bd</li>
                  </ul>
                  <ul>
                      <h5>International Islamic University Chittagong</h5>
                      <li>Kumira, Chittagong-4318, Bangladesh</li>
                      <li>IP Tel.: +8809613230505</li>
                      <li>Fax.: +8802334461930</li>
                      <li><span>Mobile Numbers remain open during office hour (08.30 AM to 04.00 PM) <br> Weekly Holiday: Thursday & Friday</span></li>
                      <li>Email: info@iiuc.ac.bd</li>
                  </ul>
                  <ul>
                      <h5>International Islamic University Chittagong</h5>
                      <li>Kumira, Chittagong-4318, Bangladesh</li>
                      <li>IP Tel.: +8809613230505</li>
                      <li>Fax.: +8802334461930</li>
                      <li>Email: info@iiuc.ac.bd</li>
                  </ul>
                  
              </div>
          </div>
      </div>
  </div>
  <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import PaginationComponent from "@/components/PaginationComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";

export default {
  name: "LocationMapView",
  components: {
    FooterComponent,
    HeaderComponent,
    PaginationComponent,
    SliderComponent
}
};
</script>

<style scope>
.about_contact_us_main {
    text-align: left;
    margin: 30px 0px;
}

.about_contact_us_main h1 {
    font-size: 16px;
    font-weight: bold;
    text-align: left;
    color: #130B63;
    margin-bottom: 20px;
}

.about_contact_us_main_map iframe {
    width: 100%;
}

.about_contact_us_main_contact h5 {
    color: #086B30;
}

.about_contact_us_main_contact ul {
    margin-top: 20px;
}

.about_contact_us_main_contact ul li span {
    color: #C79C91;
}



</style>
