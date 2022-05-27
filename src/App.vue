<template>
  <div>
    <NavBar />
    <BodyPart />
  </div>
</template>
<script>
import NavBar from "../src/components/NavBar.vue";
import BodyPart from "./components/BodyPart.vue";
export default {
  components: {
    NavBar,
    BodyPart,
  },
};
</script>
<style scoped></style>
<style lang="css" scoped>
@import "../src/css/app.css";
</style>
