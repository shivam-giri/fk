<template>
  <div class="flex items-center justify-center w-full h-screen bg-blue-500">
    <div>
      <template>
        <img class="h-64" src="https://svgsilh.com/svg/1414791.svg" alt="award image" />
      </template>
      <h3 class="mx-12 mt-10 text-3xl font-black">
        well done!
        <span class="name"></span>
      </h3>
      <p class="mx-12 text-3xl font-black">
        Your Points
        <span class="points"></span>
      </p>
      <p class="mx-12 text-3xl font-black">
        Time taken
        <span class="time_taken"></span>
      </p>
    </div>
  </div>
</template>

<script>
import { FeatherIcon } from 'vue-feather-icons'

export default {
  components: {
    FeatherIcon
  }
}
</script>