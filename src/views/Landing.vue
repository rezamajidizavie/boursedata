<template>
  <div class="landing">
    <Navbar />
    <LandingBoxes />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import LandingBoxes from "../components/LandingBoxes";

export default {
  name: "landing",
  components: {
    Navbar,
    LandingBoxes
  }
};
</script>

<style scoped>
.landing {
  height: 100vh;
}
</style>

