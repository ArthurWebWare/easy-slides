<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div class="container">
  <div class="left-sidebar">
    <div class="reader-display-container"></div>
    <div class="reader-navigation-container">
      <button>Up</button>
      <button>Down</button>
      <button>Sync</button>
    </div>
  </div>
  <div class="right-sidebar">
    <div class="input-video-container">
      <div class="video-player"></div>
      <div class="video-actions"></div>
    </div>
    <div class="chat-container">
      <div class="chat-board"></div>
      <div class="chat-actions">
        <input type="text">
        <button>send</button>
      </div>
    </div>
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
