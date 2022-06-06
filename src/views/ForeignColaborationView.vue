<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <div class="foregin_collaboration_main">
    <div class="container">
      <div class="row">
        <div class="foregin_collaboration_content">
          <h5>Foreign Collaboration</h5>
          <p>
            IIUC has signed formal academic collaboration agreement, Memorandum
            of Understanding (MoU), with the following organizations. The MoU
            includes credit transfer facility to a foreign University, exchange
            program for teachers & students etc.
          </p>
          <ol type="">
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
              <li>Portland State University (USA)</li>
          </ol>
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
  name: "ForeignColaborationView",
  components: {
    FooterComponent,
    HeaderComponent,
    PaginationComponent,
    SliderComponent,
  },
};
</script>

<style scope>
.foregin_collaboration_main {
    margin: 30px 0px;
}

.foregin_collaboration_content {
    text-align: left;
}

.foregin_collaboration_content ol li {
    list-style-type: decimal;
    color: #086B30;
    font-weight: bold;
    font-size: 14px;
    line-height: 20px;
}

.foregin_collaboration_content h5 {
    font-size: 20px;
    font-weight: bold;
    color: #130B63;
}

.foregin_collaboration_content p {
    font-size: 14px;
    
}
</style>
