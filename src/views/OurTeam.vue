<template>
  <main>
    <SiteAlerts2></SiteAlerts2>
    <strong>OurTeam page coming soon !</strong>
    <OurUpdate></OurUpdate>
    <FooterPage></FooterPage>
  </main>
</template>

<script>
import OurTeam from "../views/OurTeam.vue";
import FooterPage from "../components/FooterPage.vue";
import SiteAlerts2 from "../components/SiteAlerts2.vue";
import OurUpdate from "../components/OurUpdate.vue";

export default {
  name: "OurTeam",
  components: {
    OurTeam,
    FooterPage,
    SiteAlerts2,
    OurUpdate
  }
};
</script>

<style scoped>
main {
  padding: 100px;
}
</style>