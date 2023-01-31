<template>
  <div class="home">
    <a href="mailto:hello@acte.co">hello@acte.co</a>
   </div>
</template>

<style lang="scss">
.home{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;

  a{
    font-weight: 800;
    font-size: 1.2rem;
    letter-spacing: .05rem;
    font-family: 'Roboto', sans-serif;
  }
}
</style>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    
  },
});
</script>
