<template>
  <div id="app">
    <message>Hello there!</message>

    <message>One more</message>
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
