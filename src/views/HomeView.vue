<template>
  <div class="home">
    <HeaderComponent></HeaderComponent>
    <SliderComponent></SliderComponent>
    <NoticeComponent></NoticeComponent>
    <NewsArchiveComponent></NewsArchiveComponent>
    <AdmissionGuideComponent></AdmissionGuideComponent>
    <AboutCampusComponent></AboutCampusComponent>
    <TeamMemberComponent></TeamMemberComponent>

    <FooterComponent></FooterComponent>
  </div>
</template>

<script>


import FooterComponent from "@/components/Footer/FooterComponent.vue";
import NoticeComponent from "@/components/Home/NoticeComponent.vue";
import NewsArchiveComponent from "@/components/Home/NewsArchiveComponent.vue";
import AdmissionGuideComponent from "@/components/Home/AdmissionGuideComponent.vue";
import AboutCampusComponent from "@/components/Home/AboutCampusComponent.vue";
import TeamMemberComponent from "@/components/Home/TeamMemberComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";

export default {

  name: "HomeView",
  components: {
    FooterComponent,
    NoticeComponent,
    NewsArchiveComponent,
    AdmissionGuideComponent,
    AboutCampusComponent,
    TeamMemberComponent,
    HeaderComponent,
    SliderComponent
},
};
</script>

<style scoped>


</style>
