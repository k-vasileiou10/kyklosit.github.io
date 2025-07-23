<script setup lang="ts">

</script>

<template>
  <footer class="footer">
    <img src="@/assets/kyklos-it-high-resolution-logo-grayscale-transparent.png" alt="Footer Icon" class="footer-icon">
    <h1>I'm a footer.</h1>
  </footer>
</template>


<style scoped>
.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #dae1ff;
  border-radius: 24px;
  z-index: 1000;
  padding-left: 1rem;
  padding-right: 1rem;
  align-items: center;
  max-width: 1920px;
}

.footer-icon {
  width: 64px;
  height: 64px;
  object-fit: contain;
}

h1 {
  color: black;
}
</style>