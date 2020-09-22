<template>
  <div class="banner">
    <img :src="imgHomeBanner" alt="banner-home" />
  </div>
</template>

<script>
import imgHomeBanner from "../../assets/images/home-banner.jpg";
export default {
  name: "banner",
  data: () => {
    return {
      imgHomeBanner,
    };
  },
};
</script>

<style>
.banner img {
  width: 100%;
}
</style>