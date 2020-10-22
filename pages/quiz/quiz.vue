<template>
  <div class="flex justify-center h-full max-w-full min-h-screen bg-blue-700 item-center">
    <div class="grid table-row w-1/2 h-16 p-12">
      <div class="flex justify-between bg-white rounded-t-sm shadow-lg z-1">
        <div class="container flex items-center p-2 pl-8 pr-8">
          <h4>
            Welcome!
            <span class="name"></span>
          </h4>
        </div>
        <div class="flex items-center justify-center w-1/3 bg-blue-500">
          <span class="w-1/3">00:00</span>
        </div>
      </div>
    </div>
    <div class="absolute flex flex-col pt-20">
      <div id="questions relative"></div>
      <button
        class="flex justify-start p-4 my-40 bg-blue-300 border-0 shadow-lg color-white"
      >Next Question</button>
    </div>
  </div>
</template>
