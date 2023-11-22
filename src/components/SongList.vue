<script setup>
import { ref } from "vue";
import { invoke } from "@tauri-apps/api/tauri";

const songList = [
  {
    id: 1,
    name: "歌曲1",
    url: '1',
  },
  {
    id: 2,
    name: "歌曲2",
    url: '1',
  },
];



</script>

<template>
  <div class="songlist">
    songlist
  </div>

</template>

<style scoped>
.songlist {
  color: #fff;
  background: #000;
  font-size: 16px;
  padding: 10px;
}

</style>