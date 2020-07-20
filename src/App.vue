<template>
  <div id="app">
    <h1>keep array data inside local JSON file for Vue App</h1>
    <Alphabet class="center" />

    <section class="title">
    </section>
  </div>
</template>

<script>
import Alphabet from "./components/alphabet.vue";

export default {
  name: "App",
  components: {
    Alphabet,
  },
};
</script>

<style lang="sass">
#app
  font-family: Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px
  margin: 60px 18px 0 18px
  max-width: 960px
  width: 100%

body
  display: flex
  justify-content: center
  align-items: center

.center
  display: flex
  justify-content: center
  align-items: center
*
  box-sizing: border-box

  .title
    margin-top: 120px
    text-align: left
</style>
