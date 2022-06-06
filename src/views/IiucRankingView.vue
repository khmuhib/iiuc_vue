<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <div class="iiuc_ranking_main">
    <div class="container">
      <div class="row">
        <h3>IIUC Ranking</h3>
        <p>
          IIUC has been ranked 23rd of the top ranking Universities(Total=147,
          both Public and Private) in Bangladesh, by the Webometrics Ranking of
          World Universities
        </p>
        <button>View Ranking Page</button>
      </div>
      <div class="row">
        <div class="iiuc_ranking_card">
          <h5>UGC’s ranking & BAETE’s accreditation</h5>
          <p>
            IIUC is among the top graded 9 Private Universities of Bangladesh
            Graded by the high powered team constituted by the Prime Minister in
            2004 headed by the Chairman of UGC for evaluating the standard &
            quality of existing 36 (Thirty Six) Private Universities.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="iiuc_ranking_card">
          <h5>UGC’s ranking & BAETE’s accreditation</h5>
          <p>
            IIUC is among the top graded 9 Private Universities of Bangladesh
            Graded by the high powered team constituted by the Prime Minister in
            2004 headed by the Chairman of UGC for evaluating the standard &
            quality of existing 36 (Thirty Six) Private Universities.
          </p>
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
  name: "IiucRankingView",
  components: {
    FooterComponent,
    HeaderComponent,
    PaginationComponent,
    SliderComponent,
  },
};
</script>

<style scope>
.iiuc_ranking_main {
    text-align: left;
    margin: 30px 0px;
}

.iiuc_ranking_main h3{
    color: #130B63;
    font-size: 16px;
    font-weight: bold;
}

.iiuc_ranking_main p {
    font-size: 14px;
}

.iiuc_ranking_main button {
    display: block;
    width: 15%;
    margin: auto;
    border: none;
    outline: none;
    border: 1px solid #130B63;
    background-color: white;
    padding: 5px 0px;
    font-size: 14px;
}

.iiuc_ranking_card h5 {
    font-size: 14px;
    font-weight: bold;
    color: #086B30;
}

.iiuc_ranking_card {
    margin: 10px 0px;
}
</style>
