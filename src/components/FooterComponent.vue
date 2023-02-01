<template>
  <footer class="nav">
    <p>a.c.t.e. | {{ new Date().getFullYear()  }}</p>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'FooterComponent',
});
</script>

<style scoped lang="scss">
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 5px 10px;
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;

  p{
    margin: 0;
    padding: 0;
    font-size: .8rem;
  }
}
</style>
