<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import SongList from "./components/SongList.vue";
import PalyerRoom from "./components/PalyerRoom.vue";
</script>

<template>
  <div class="container">

    <SongList />
    <PalyerRoom />
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
