<template>
  <div class="container">
    <img alt="Vue logo" src="../assets/logo-m.png" />
    <h1>The Millionaire</h1>
    <StartButton></StartButton>
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
.container {
  background-color: #10103a;
  color: #fff;
  padding: 30px;
  height: 100vh;
  text-align: center;

  h1 {
    font-size: 50px;
    margin-top: 50px;
  }
}

img {
  width: 40%;
  max-width: 250px;
}
</style>
