<template>
  <div class="flex justify-center item-center max-w-full min-h-screen h-full bg-blue-700">
    <div class="grid table-row w-1/2 h-16 p-12">
      <div class="flex justify-between rounded-t-sm bg-white shadow-lg z-1">
        <div class="flex items-center container p-2 pl-8 pr-8 ">
          <h4>
            Welcome!
            <span class="name"></span>
          </h4>
        </div>
        <div class="w-1/3 flex items-center justify-center bg-blue-500">
          <span class="w-1/3">00:00</span>
        </div>
      </div>
    </div>
    <div class="flex flex-col absolute pt-20">
      <div id="questions relative"></div>
      <button
        class="flex my-40 justify-start border-0 bg-blue-300 p-4 color-white shadow-lg"
        @click="next()"
      >Next Question</button>
    </div>
  </div>
</template>
