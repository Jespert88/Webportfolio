<template>
  <div class="Index, indexFlex">
    <!-- Sidebar -->
    <div class="leftContainer">
      <appSideBar />
    </div>

    <!-- Main Content -->
    <div class="rightContainer">
      <div class="margin-xl">
        <div class="centerContainer">
          <h1 class="title-lg">Tjena Jesper här!</h1>
        </div>
      </div>

      <div class="padding-lg">
        <p class="text-sm">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book. It has survived not only
          five centuries, but also the leap into electronic typesetting,
          remaining essentially unchanged. It was popularised in the 1960s with
          the release of Letraset sheets containing Lorem Ipsum passages, and
          more recently with desktop publishing software like Aldus PageMaker
          including versions of Lorem Ipsum.
        </p>
      </div>

      <div class="centerContainer">
        <h1 class="title-lg">Heroku projekt</h1>
      </div>

      <div class="centerContainer">
        <div class="padding-lg">
          <div class="grid-col-3">
            <a href="https://naturkollen.herokuapp.com/" class="projectLinks">
              <img
                src="../assets/naturkollen.png"
                class="img-fluid, projectImg"
              />
              <p class="text-sm">Naturkollen</p></a
            >
            <a
              href="https://react-template-oak.herokuapp.com/"
              class="projectLinks"
            >
              <img src="../assets/movies.png" class="img-fluid, projectImg" />
              <p class="text-sm">React movie app</p></a
            >
            <a
              href="https://gearfornature.herokuapp.com/#/"
              class="projectLinks"
            >
              <img
                src="../assets/gearForNature.png"
                class="img-fluid, projectImg"
              />
              <p class="text-sm">gearForNature</p></a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import appSideBar from "@/components/appSideBar.vue";

export default {
  name: "Index",
  components: {
    appSideBar,
  },
};
</script>
<style>
@import "../assets/css/Index.css";
@import "../assets/css/globalStyles.css";
</style>