<script setup lang="ts">

</script>

<template>
  <header class="header">
    <div class="header-content">
      <div class="header-icon-title">
        <img src="/kyklos-it-high-resolution-logo-transparent.png" alt="Header Icon" class="header-icon"/>
      </div>

      <div class="header-title">
        <h1>Est. 2025</h1>
      </div>

      <div class="header-navbar">
        <button class="header-btn">Home</button>
        <button class="header-btn">Info</button>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #6683ff;
  border-radius: 24px;
}

.header-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1920px;
  margin: 0 auto;
  padding-left: 1rem;
  padding-right: 1rem;
}

.header-icon {
  display: block;
  width: 200px;
  height: 110px;
  object-fit: contain;
}

.header-title {
  font-size: 1rem;
  font-weight: bold;
  margin: 0 auto;
  text-align: center;
  flex: 1;
}

.header-navbar {
  display: flex;
  gap: 0.5rem;
}

.header-btn {
  padding: 1.0rem 1.6rem;
  font-size: 1.4rem;
  background-color: #f3f5ff;
  border: none;
  border-radius: 24px;
  cursor: pointer;
  transition: background-color 0.23s;
}

.header-btn:hover {
  background-color: #859cff;
}
</style>
