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

      <div class="centerContainer">
        <div class="padding-lg">
          <p class="text-sm">
            Är en kille som brinner för natur och teknik. Är ständigt
            instresserad av lära mig nya saker inom programmering och teknik.<br />
            Dessa webbappar är hobbyprojekt jag har byggt för att lära mig
            ramverken och för att visa vad jag kan göra just nu.
          </p>
        </div>
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
              <h1 class="title-sm">Naturkollen</h1>
              <br />
              <p class="text-sm">Byggd med Vue Cli 3</p>
              <img src="../assets/logo.png" class="img-fluid, vueIcon" />
            </a>

            <a
              href="https://react-template-oak.herokuapp.com/"
              class="projectLinks"
            >
              <img src="../assets/movies.png" class="img-fluid, projectImg" />
              <h1 class="title-sm">React movie app</h1>
              <br />
              <p class="text-sm">Byggd med React + The MovieDB API</p>
              <img src="../assets/reactIcon.svg" class="img-fluid, vueIcon" />
            </a>

            <a
              href="https://gearfornature.herokuapp.com/#/"
              class="projectLinks"
            >
              <img
                src="../assets/gearForNature.png"
                class="img-fluid, projectImg"
              />
              <h1 class="title-sm">gearForNature</h1>
              <br />
              <p class="text-sm">Byggd med Vue Cli 3</p>
              <img src="../assets/logo.png" class="img-fluid, vueIcon" />
            </a>
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