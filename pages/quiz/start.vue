<template>

  <div class="flex justify-center item-center max-w-full min-h-screen h-full bg-blue-700">
      <div class="pt-20">
        <form
          class=" block container p-5 rounded-3xl text-white text-3xl cursor-pointer transform motion-safe:hover:-translate-y-1 motion-safe:hover:scale-110 transition ease-in-out duration-300"
          name="welcome_form"
          onsubmit="submitForm(event)"
        >
          <input class="block container p-4 text-center px-4 py-2 outline-none" type="text" name="name" placeholder="Enter Your Name"/>
          <nuxt-link to = "/quiz/quiz">
          <button class="block container p-5 rounded-3xl text-white text-3xl cursor-pointer transform motion-safe:hover:-translate-y-1 motion-safe:hover:scale-110 transition ease-in-out duration-300">Start Quiz</button>
          </nuxt-link>
        </form>
      </div>
    </div>

 
</template>

<script>
</script>
<style scoped></style>
