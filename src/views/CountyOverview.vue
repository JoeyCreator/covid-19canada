<template>
  <main>
    <SiteAlerts></SiteAlerts>
    <SocialMedia></SocialMedia>
    <h1>CountyOverview</h1>
    <iframe
      src="https://covid19canada.maps.arcgis.com/apps/opsdashboard/index.html#/2772c0489f43411ca9493fc5888fbe67"
      height="550"
      width="100%"
    ></iframe>
    <p>Covid-19Tracker</p>
    <FooterPage></FooterPage>
  </main>
</template>

<script>
import CountyOverview from "../views/CountyOverview.vue";
import FooterPage from "../components/FooterPage.vue";
import SiteAlerts from "../components/SiteAlerts.vue";
import SocialMedia from "../components/SocialMedia.vue";

export default {
  name: "CountyOverview",
  components: {
    CountyOverview,
    FooterPage,
    SiteAlerts,
    SocialMedia
  }
};
</script>

<style scoped>
main {
  padding: 100px;
}
</style>