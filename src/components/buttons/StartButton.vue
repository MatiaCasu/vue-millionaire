<template>
  <router-link to="/Play" tag="button">Start Game</router-link>
</template>

<script>
export default {
  name: "StartButton",
};
</script>

<style scoped lang="scss">
button {
  border: white 0.2em solid;
  color: #fff;
  font-size: 30px;
  background: none;
  padding: 0.5em 1em;
  margin: 1.8em;
  cursor: pointer;

  &:hover{
    border-color: #fff;
    color: #fff;
    background: #ffb52c;

  }
}
</style>
