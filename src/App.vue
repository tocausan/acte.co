<template>
  <NavComponent />
  <router-view />
  <FooterComponent />
</template>

<style lang="scss">
* {
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100vw;
  height: 100vh;
  overflow: scroll;
}

@media screen and (max-width: 768px) {
  #app {
    height: inherit;
  }
}
</style>

<script lang="ts">
import { defineComponent } from "vue";
import NavComponent from "@/components/NavComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default defineComponent({
  name: "App",
  components: {
    NavComponent,
    FooterComponent,
  },
});
</script>
