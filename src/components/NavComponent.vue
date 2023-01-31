<template>
  <nav class="nav">
    <router-link to="/" class="logo">
      <img src="/acte-logo.png" alt="acte logo">
    </router-link>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'NavComponent',
});
</script>

<style scoped lang="scss">
nav {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  padding: 10px;
  position: fixed;
  top: 0;
  left: 0;

  a {
    display: flex;

    margin-right: 20px;
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #3447c4;
    }

    img{
      width: 80px;
    }
  }
}
</style>
