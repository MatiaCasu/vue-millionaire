<template>
  <div class="container">
    <h1>Let's Play!</h1>
    <QuestionButton text="2+2=?"></QuestionButton>
  </div>
</template>

<script>
// @ is an alias to /src
import QuestionButton from "@/components/buttons/QuestionButton.vue";

export default {
  name: "Play",
  components: {
    QuestionButton
  }
}
</script>

<style scoped lang="scss">
  @import "@/assets/scss/_commons";
</style>