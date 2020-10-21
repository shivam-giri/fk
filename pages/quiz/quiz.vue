<template>
  <div class="flex items-center justify-center w-full h-screen bg-blue-500">
    <div class="w-full h-12 grid-rows-4 bg-white bg-gray-500 rounded-t-sm shadow-md quiz z-1">
      <div class="flex justify-between rounded-t-sm bg-white shadow-lg rounded-sm">
        <div class="flex items-center h-full px-6">
          <h4>
            Welcome!
            <span class="name"></span>
          </h4>
        </div>
        <div class="flex items-center justify-center h-full w-full bg-blue-500 color-white">
          <span class="time">00:00</span>
        </div>
      </div>
    </div>
    <div class="bg-blue-300">
      <div id="questions relative"></div>
      <button
        class="flex justify-end border-0 bg-blue-700 p-4 color-white shadow-lg"
        @click="next()"
      >Next Question</button>
    </div>
  </div>
</template>
