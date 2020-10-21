<template>

  <div class="flex justify-center item-center max-w-full max-h-screen h-full bg-blue-700">
      <div class="welcome_text">
        <form
          class="welcome_form"
          name="welcome_form"
          onsubmit="submitForm(event)"
        >
          <input class="block container p-4 text-center px-4 py-2 outline-none" type="text" name="name" placeholder="Enter Your Name"/>
          <button class="block container p-5 rounded-3xl text-white text-3xl cursor-pointer transform motion-safe:hover:-translate-y-1 motion-safe:hover:scale-110 transition ease-in-out duration-300">Start Quiz</button>
        </form>
      </div>
    </div>

 
</template>

<script>
export default {
  methods: {
    start() {
      this.$router.push('/quiz/quiz')
    },
  },
}
</script>
<style scoped></style>
