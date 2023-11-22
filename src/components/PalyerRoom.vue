<script setup>
import { ref } from "vue";
import { invoke } from "@tauri-apps/api/tauri";




</script>

<template>
  <div class="playerroom">
    playerroom
  </div>

</template>

<style scoped>
.sensor-list {
  display: flex;
  justify-content: center;
}
.sensor-list .item {
  padding: 10px 15px;
  margin: 10px 15px;
  box-shadow: 0 0 3px rgba(3,3,3, 0.2);
  border-radius: 3px;
}

.sensor-statistic {
  display: flex;
  justify-content: center;
}
.sensor-statistic .item {
  padding: 10px 15px;
  margin: 10px 15px;
  box-shadow: 0 0 3px rgba(3,3,3, 0.2);
  border-radius: 3px;
}


</style>