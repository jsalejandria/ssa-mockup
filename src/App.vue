<template>
  <div>
    <Top />
    <Features />
    <Action />
    <Bottom />
  </div>
</template>

<script>
import Top from "./components/Top.vue";
import Features from "./components/Features.vue";
import Action from "./components/Action.vue";
import Bottom from "./components/Bottom.vue";

export default {
  name: "App",
  components: {
    Top,
    Features,
    Action,
    Bottom,
  },
};
</script>

<style lang="scss">
@import "./assets/style.scss";

#app {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
