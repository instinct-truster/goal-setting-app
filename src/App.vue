<template>
  <main class="main-wrapper">
    <h1 class="app-title">Carpe Diem!</h1>
    <p class="app-subtitle">
      Create and take the steps required to SEIZE THIS DAY!
    </p>
    <input type="text" />
    <button>+ Add</button>
  </main>
</template>

<script setup lang="ts"></script>

<style scoped>
.app-title {
  font-family: "Luckiest Guy", cursive;
  color: white;
  font-size: 60px;
  letter-spacing: 0.5px;
  -webkit-text-stroke: 2px darkslategray;
  margin-top: 60px;
  margin-bottom: 0;
}

.app-subtitle {
  font-weight: bold;
}

.main-wrapper {
  max-width: 600px;
  margin: 0 auto;
}
</style>
