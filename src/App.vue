<template>
  <div id="app">

    <h4 class="demo__heading">Step 16 — Webpack and vue-cli</h4>

    <message>Hello there! I'm Message component</message>

    <message>And I'm Message component too! Hi!</message>
  </div>
</template>

<script>
  import message from './components/Message.vue'

  export default {
    name: 'app',

    components: {
      message
    },

    data () {
      return {

      }
    }
  }
</script>

<style>

</style>
