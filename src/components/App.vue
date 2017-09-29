<template>
  <div>
    <h1>{{ msg }}</h1>
    <hiragana></hiragana>
  </div>
</template>

<script>
import Hiragana from './hiragana/Hiragana.vue'

export default {

  components: {
    Hiragana
  },

  data () {
    return {
      msg: 'Hello, World!'
    }
  }
}
</script>

<style>

</style>
