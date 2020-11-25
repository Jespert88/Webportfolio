<template>
  <div id="Sidebar">
    <div class="centerContainer, padding-lg">
      <img src="../assets/selfie.jpg" class="img-fluid" id="Selfie" />
    </div>

    <div class="centerContainer">
      <h1 class="text-center, title-sm-white">Jesper Truedsson</h1>
      <h1 class="text-center, text-sm-white">Junior webbutvecklare</h1>
    </div>

    <div class="centerContainer">
      <div class="flex">
        <div class="padding-lg">
          <a href="https://www.linkedin.com/in/jesper-truedsson-812806142/">
            <img src="../assets/linkedin.png" class="img-fluid, linkIcons" />
            <p class="text-sm-white">LinkedIn</p>
          </a>
        </div>
        <div class="padding-lg">
          <a href="mailto:jespertruedsson88@gmail.com">
            <img src="../assets/gmail.png" class="img-fluid, linkIcons" />
            <p class="text-sm-white">Gmail</p>
          </a>
        </div>
      </div>
    </div>

    <div class="centerContainer, padding-sm">
      <div class="flex">
        <img src="../assets/smartphone.png" class="img-fluid" id="phoneIcon" />
        <p class="text-sm-white"><b>Mobil:</b> 0768970571</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {},
  data() {
    return {};
  },
  methods: {},
};
</script>

<style>
@import "../assets/css/appSideBar.css";
@import "../assets/css/globalStyles.css";
</style>