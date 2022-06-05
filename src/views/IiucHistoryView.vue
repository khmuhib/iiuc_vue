<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <IiucHistoryCompornent></IiucHistoryCompornent>
  <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import IiucHistoryCompornent from "@/components/IiucHistoryCompornent.vue";
import PaginationComponent from "@/components/PaginationComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";

export default {
  name: "IiucHistoryView",
  components: {
    FooterComponent,
    HeaderComponent,
    IiucHistoryCompornent,
    PaginationComponent,
    SliderComponent
}
};
</script>

<style></style>
