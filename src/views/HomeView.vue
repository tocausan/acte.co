<template>
  <div class="home">
    <a href="mailto:hello@acte.co">hello@acte.co</a>
  </div>
</template>

<style lang="scss" scoped>
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  overflow: hidden;

  a {
    font-weight: 800;
    font-size: 1.2rem;
    letter-spacing: 0.05rem;
    font-family: "Roboto", sans-serif;
  }
}

@media screen and (max-width: 768px) {
  .home {
    padding-top: 200px;

    a {
      font-weight: inherit;
    }
  }
}
</style>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomeView",
  components: {},
});
</script>
