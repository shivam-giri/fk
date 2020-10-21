<template>
  <div class="container">
    <div class="wrapper">
      <div class="quiz">
        <div class="quiz_header">
          <div class="quiz_user">
            <h4>Welcome! <span class="name"></span></h4>
          </div>
          <div class="quiz_timer">
            <span class="time">00:00</span>
          </div>
        </div>
        <div class="quiz_body">
          <div id="questions"></div>

          <button class="btn-next" onclick="next()">Next Question</button>
        </div>
      </div>
    </div>
    <NuxtLink to="/"> Go to / </NuxtLink>
  </div>
</template>

<script>
export default {
  asyncData() {
    return new Promise((resolve) => {
      setTimeout(function () {
        resolve({})
      }, 1000)
    })
  },
}
</script>

<style scoped>
.container {
  font-size: 20px;
  text-align: center;
  padding-top: 100px;
}
</style>