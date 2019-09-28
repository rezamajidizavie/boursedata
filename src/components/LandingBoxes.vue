<template>
  <div class="landing-boxes d-flex justify-content-center w-100 align-items-center">
    <div class="justify-content-center d-flex w-100 row">
      <a href="#" class="p-4 col-4 landing-box">فهرست نماد ها</a>
      <a href="#" class="p-4 col-4 landing-box">فهرست تحلیل ها</a>
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
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 25px;
  transition: 0.3s all;
  text-decoration: none;
  color: white;
  background-image: linear-gradient(
    to right top,
    #051937,
    #004d7a,
    #008793,
    #00bf72,
    #a8eb12
  );
}
.landing-box {
  height: 300px;
}

.landing-box:hover {
  transform: scale(1.03);
  transition: 0.3s all;
  text-decoration: none;
}

.landing-boxes {
  height: 100%;
}
</style>
