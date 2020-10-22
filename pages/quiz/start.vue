<template>
  <div class="flex justify-center h-full max-w-full min-h-screen bg-blue-700 item-center">
    <div class="pt-20">
      <div>
        <h1
          class="font-serif text-4xl text-center text-gray-800 divide-purple-900 animate-bounce animate-pulse"
        >Welcome To "Qwiz World" !!</h1>
      </div>
      <form
        class="container block p-5 mt-20 text-3xl text-white transition duration-300 ease-in-out transform cursor-pointer rounded-3xl motion-safe:hover:-translate-y-1 motion-safe:hover:scale-110"
        name="welcome_form"
        onsubmit="submitForm(event)"
      >
        <input
          class="container block p-4 px-4 py-2 text-center outline-none rounded-3xl"
          type="text"
          name="name"
          placeholder="Enter Your Name"
        />
        <nuxt-link to="/quiz/quiz">
          <button
            class="container block p-4 mt-4 text-3xl text-white transition duration-300 ease-in-out transform bg-blue-900 cursor-pointer rounded-3xl motion-safe:hover:-translate-y-1 motion-safe:hover:scale-110"
          >Start Quiz</button>
        </nuxt-link>
      </form>
    </div>
  </div>
</template>

<script>
</script>
<style scoped></style>
