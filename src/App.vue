<template>
  <main class="main-wrapper">
    <h1 class="app-title">Carpe Diem!</h1>
    <p class="app-subtitle">
      Create and take the steps required to SEIZE THIS DAY!
    </p>
    <div class="new-goal-wrapper">
      <input
        class="new-goal-input"
        type="text"
        placeholder="Add your new goal here..." />
      <button class="new-goal-button">+ Set</button>
    </div>
  </main>
</template>

<script setup lang="ts"></script>

<style scoped>
.app-title {
  font-family: "Luckiest Guy", cursive;
  color: white;
  font-size: 60px;
  letter-spacing: 0.5px;
  -webkit-text-stroke: 2px rgb(119, 119, 119);
  margin-top: 60px;
  margin-bottom: 0;
}

.app-subtitle {
  color: white;
  font-weight: bold;
}

.main-wrapper {
  max-width: 600px;
  margin: 0 auto;
}

.new-goal-wrapper {
  display: flex;
}

.new-goal-input {
  margin-top: 8px;
  border: none;
  border-top-left-radius: 12px;
  border-bottom-left-radius: 12px;
  padding: 16px;
  flex: 1;
  letter-spacing: 1px;
  box-shadow: 2px 2px 8px 0 #d0d0d0;
}

.new-goal-button {
  background-image: linear-gradient(
    to bottom left,
    rgb(244, 154, 19),
    rgb(207, 72, 35)
  );
  font-weight: bold;
  color: white;
  border: none;
  margin-top: 8px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  padding: 16px;
  box-shadow: 2px 2px 8px 0 #d0d0d0;
}
</style>
