<template>
  <div class="h-1/3 bg-gray-300 flex items-center justify-center border-b">
    <p class="text-gray-500">Video Placeholder</p>
  </div>

  <div class="h-5 bg-gray-200 border-b"></div>

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

  <div class="flex-1 flex flex-col bg-gray-50">
    <div class="flex-1 overflow-y-scroll p-4">
      <div class="mb-4">
        <p class="bg-white p-2 rounded-lg shadow text-sm">Пример сообщения</p>
      </div>
      <div class="mb-4">
        <p class="bg-blue-100 p-2 rounded-lg shadow text-sm">Ответ</p>
      </div>
    </div>
    <div class="flex items-center p-4 border-t bg-white">
      <input type="text" class="flex-1 p-2 border rounded-lg" placeholder="Введите сообщение...">
      <button class="ml-4 px-4 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600">Отправить</button>
    </div>
  </div>

</template>