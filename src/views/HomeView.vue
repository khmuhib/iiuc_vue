<template>
  <div class="home">
    <HeaderComponent></HeaderComponent>
    <!-- <HeaderTopComponent></HeaderTopComponent>
    <HeaderBottomComponent></HeaderBottomComponent>
    <HeaderMainMenuComponent></HeaderMainMenuComponent>
    <SliderComponent></SliderComponent> -->
    <NoticeComponent></NoticeComponent>
    <NewsArchiveComponent></NewsArchiveComponent>
    <AdmissionGuideComponent></AdmissionGuideComponent>
    <AboutCampusComponent></AboutCampusComponent>
    <TeamMemberComponent></TeamMemberComponent>

    <CallToAction></CallToAction>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>

//import '../assets/js/jquery.min.js'
//import '../assets/js/owl.carousel.min.js';

// @ is an alias to /src
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import CallToAction from "@/components/Footer/CallToAction.vue";
import NoticeComponent from "@/components/Home/NoticeComponent.vue";
import NewsArchiveComponent from "@/components/Home/NewsArchiveComponent.vue";
import AdmissionGuideComponent from "@/components/Home/AdmissionGuideComponent.vue";
import AboutCampusComponent from "@/components/Home/AboutCampusComponent.vue";
import TeamMemberComponent from "@/components/Home/TeamMemberComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";

export default {

  name: "HomeView",
  components: {
    FooterComponent,
    CallToAction,
    NoticeComponent,
    NewsArchiveComponent,
    AdmissionGuideComponent,
    AboutCampusComponent,
    TeamMemberComponent,
    HeaderComponent
},
};
</script>

<style scoped>
/*@import "../assets/css/owl.carousel.min.css";
@import "../assets/css/owl.theme.default.min.css";*/
</style>
