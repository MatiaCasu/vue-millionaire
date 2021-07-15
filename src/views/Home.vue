<template>
  <div class="container">
    <img alt="Vue logo" src="../assets/img/logo-m.png" />
    <h1>The Millionaire</h1>
    <StartButton text="Start Game"></StartButton>
  </div>
</template>

<script>
// @ is an alias to /src
import StartButton from "@/components/buttons/StartButton.vue";

export default {
  name: "Home",
  components: {
    StartButton,
  },
};
</script>

<style lang="scss" scoped>
  @import "@/assets/scss/_commons";

  h1 {
    font-size: 50px;
    margin-top: 50px;
  }

  img {
    width: 40%;
    max-width: 250px;
    min-width: 200px;
  }
</style>
