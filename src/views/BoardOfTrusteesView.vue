<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <BoardOfTrusteesComponent></BoardOfTrusteesComponent>
  <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import PaginationComponent from "@/components/PaginationComponent.vue";
import BoardOfTrusteesComponent from "@/components/BoardOfTrusteesComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";

export default {
  name: 'BoardOfTrusteesView',
  components: {
    FooterComponent,
    HeaderComponent,
    PaginationComponent,
    BoardOfTrusteesComponent,
    SliderComponent
}

}
</script>

<style>
</style>