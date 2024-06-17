<script setup lang="ts">
import NavBar from "./components/NavBar.vue"

</script>

<template>
  <div class="background">
    <NavBar></NavBar>
    <a>
      <img src="./assets/Spart Logo@300x-8.png" class="logo fade-in-element" alt="Vue logo" />
    </a>
  </div>
</template>

<style scoped>

.logo {
  height: 30em;
  margin: 0 0 0 0;
  will-change: filter;
  transition: filter 300ms;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.fade-in-element {
  opacity: 1;
  animation: fadeIn 5s;
}
</style>
