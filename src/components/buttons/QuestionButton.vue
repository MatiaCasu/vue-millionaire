<template>
  <div class="base-btn">
    <hr>
    <router-link to="/" tag="button"><span class="left"></span>{{text}}<span class="right"></span></router-link>  
  </div>
</template>

<script>
  export default {
    name: "QuestionButton",
    props: {
      text: {
        type: String,
        require: true
      }
    }
  }
</script>

<style lang="scss">
  @import "@/assets/scss/_baseButton";
</style>