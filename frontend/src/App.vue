<script setup lang="ts">

import DocumentView from "./components/DocumentView.vue";
import VideoBoard from "./components/VideoBoard.vue";
</script>

<template>
  <div class="flex flex-row h-screen justify-between">
    <div class="left-sidebar w-1/2 flex flex-col bg-white border-r">
      <DocumentView/>
    </div>
    <div class="right-sidebar w-1/2 flex flex-col">
      <VideoBoard/>
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
