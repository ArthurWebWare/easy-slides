<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
import PDF from "pdf-vue3"
</script>

<template>
<div class="flex flex-row h-screen justify-between">
  <div class="left-sidebar w-1/2 flex flex-col bg-white border-r">
    <!-- PDF Viewer -->
    <div class="flex-1  overflow-y-hidden p-4">
      <div class="h-[100%] border rounded-lg">
        <PDF src="https://hymhub.github.io/pdf-vue3/mastering_javascript_design_patterns_fragment.pdf" pdfWidth="70vh" />
        <!-- <PDF :src="BASE64" /> -->
        <!-- <PDF :src="Uint8Array" /> -->
      </div>
    </div>

    <!-- Кнопки управления -->
    <div class="flex justify-around p-4 border-t">
      <button class="w-12 h-12 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        <span class="text-xl">⬇</span>
      </button>
      <button class="w-12 h-12 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        <span class="text-xl">⬆</span>
      </button>
      <button class="w-12 h-12 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        <span class="text-xl">⚙</span>
      </button>
    </div>
  </div>
  <!-- Правая половина -->
  <div class="right-sidebar w-1/2 flex flex-col">
    <!-- Видео -->
    <div class="h-1/3 bg-gray-300 flex items-center justify-center border-b">
      <p class="text-gray-500">Video Placeholder</p>
    </div>

    <!-- Пустой блок -->
    <div class="h-5 bg-gray-200 border-b"></div>

    <!-- Кнопки управления -->
    <div class="h-16 flex justify-around items-center border-b bg-white">
      <button class="w-16 h-16 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        MIC
      </button>
      <button class="w-16 h-16 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        ✋
      </button>
      <button class="w-16 h-16 bg-gray-200 rounded-full flex items-center justify-center hover:bg-gray-300">
        EXIT
      </button>
    </div>

    <!-- Блок чата -->
    <div class="flex-1 flex flex-col bg-gray-50">
      <div class="flex-1 overflow-y-scroll p-4">
        <!-- Сообщения -->
        <div class="mb-4">
          <p class="bg-white p-2 rounded-lg shadow text-sm">Пример сообщения</p>
        </div>
        <div class="mb-4">
          <p class="bg-blue-100 p-2 rounded-lg shadow text-sm">Ответ</p>
        </div>
      </div>
      <!-- Поле ввода -->
      <div class="flex items-center p-4 border-t bg-white">
        <input type="text" class="flex-1 p-2 border rounded-lg" placeholder="Введите сообщение...">
        <button class="ml-4 px-4 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600">Отправить</button>
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
