<template>
  <HeaderComponent></HeaderComponent>
  <PaginationComponent></PaginationComponent>
  <IiucHistoryCompornent></IiucHistoryCompornent>
  <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import IiucHistoryCompornent from "@/components/IiucHistoryCompornent.vue";
import PaginationComponent from "@/components/PaginationComponent.vue";

export default {
  name: "IiucHistoryView",
  components: {
    FooterComponent,
    HeaderComponent,
    IiucHistoryCompornent,
    PaginationComponent
}
};
</script>

<style></style>
