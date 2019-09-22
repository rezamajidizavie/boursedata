<template>
  <div class="landing-boxes d-flex justify-content-center align-items-center">
    <div class="justify-content-center d-flex">
      <div class="p-4 landing-box">فهرست نماد ها</div>
      <div class="p-4 landing-box">فهرست تحلیل ها</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingBoxes",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.landing-box {
  margin: 10px;
  border-radius: 10px;
  -webkit-box-shadow: 0px 0px 10px -5px rgba(133, 119, 133, 1);
  -moz-box-shadow: 0px 0px 10px -5px rgba(133, 119, 133, 1);
  box-shadow: 0px 0px 10px -5px rgba(133, 119, 133, 1);
}
.landing-boxes {
}
</style>
