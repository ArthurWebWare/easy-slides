<script setup lang="ts">
  import PDF from "pdf-vue3";
</script>

<template>
  <!-- PDF Viewer -->
  <div class="flex-1  overflow-y-hidden p-4">
    <div class="h-[100%] border rounded-lg">
      <PDF src="https://hymhub.github.io/pdf-vue3/mastering_javascript_design_patterns_fragment.pdf" pdfWidth="70vh"/>
      <!-- <PDF :src="BASE64" /> -->
      <!-- <PDF :src="Uint8Array" /> -->
    </div>
  </div>

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

</template>

<style scoped>

</style>