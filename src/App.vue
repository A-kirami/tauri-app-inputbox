<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Greet from "./components/Greet.vue";
</script>

<template>
  <div class="container">
    <div>
      <h2>InputBox</h2>
      <h3>Not affected</h3>
      <h3>Not affected</h3>
      <h3>Not affected</h3>
      <input id="a" type="text" />
      <h3>Affected by a</h3>
      <h3>Affected by a</h3>
      <h3>Affected by a</h3>
    </div>
    <label>Affected by a</label>
    <label>Affected by a</label>
    <label>Affected by a</label>
    <input id="b" type="text" />
    <label>Affected by a and b</label>
    <label>Affected by a and b</label>
    <label>Affected by a and b</label>
  </div>
</template>

<style scoped>
.logo.vite:hover {
  filter: drop-shadow(0 0 2em #747bff);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #249b73);
}
</style>
