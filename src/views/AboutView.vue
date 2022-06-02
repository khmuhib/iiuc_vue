<template>

    <header>
      <Navbar />
      
    </header>
  
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  name: "AboutView",
  components: {
    Navbar
  }

};
</script>

<style scoped>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'montserrat', sans-serif;
}

header {
  width: 100vw;
  background-color: #222;
  padding: 15px;
}

</style>
