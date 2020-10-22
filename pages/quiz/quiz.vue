<template>
  <div class="h-full max-w-full min-h-screen bg-blue-800">
    <div class="w-full h-16 p-12 mx-auto lg:w-2/3 z-1">
      <div class="flex justify-between bg-white rounded-t-sm">
        <div class="container flex items-center p-4 pl-8 shadow-lg">
          <h4>Welcome!</h4>
        </div>
        <div class="flex items-center justify-center w-1/3 bg-blue-500">
          <span class="w-1/3">00:00</span>
        </div>
      </div>
      <!-- questions area  -->
      <div class="p-5 pl-10 bg-gray-300">
        <h3 class="pb-4 text-3xl font-black">Q) What is Full Form of Ram?</h3>
        <div>
          <div class="block w-1/3 p-3 pl-5 mb-5 ml-3 bg-white border-2 shadow-lg rounded-3xl">
            <button>
              <p>Random Assess Memory</p>
            </button>
          </div>
          <div class="block w-1/3 p-3 pl-5 mb-5 ml-3 bg-white border-2 shadow-lg rounded-3xl">
            <button>
              <p>Random Assess Memory</p>
            </button>
          </div>
          <div class="block w-1/3 p-3 pl-5 mb-5 ml-3 bg-white border-2 shadow-lg rounded-3xl">
            <button>
              <p>Random Assess Memory</p>
            </button>
          </div>
          <div class="block w-1/3 p-3 pl-5 mb-5 ml-3 bg-white border-2 shadow-lg rounded-3xl">
            <button>
              <p>Random Assess Memory</p>
            </button>
          </div>
          <div class="block w-1/4 p-2 mb-5 ml-4 bg-blue-800 border-2 shadow-lg rounded-3xl">
            <nuxt-link to="/quiz/end">
              <button class="p-2 ml-5 font-bold text-white" @click="go()">Next Question</button>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
    <div class="absolute flex flex-col pt-20">
      <div id="questions relative"></div>
    </div>
  </div>
</template>
<script>
export default {
  methods:{
    go(){
      // this.$router.push('/end')
      <nuxt-link to = "/quiz/end"></nuxt-link>

    }
  }
}
</script>