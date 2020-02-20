<template>
 <div id="q-app">Bonjour !</div>
</template>

<script>
import { global } from './app/global'

/* eslint-disable no-unused-vars */
// import MonComp from './components/MonComp.vue'

export default {
  name: 'App',

  // components: { MonComp },

  mounted() {
    global.appVue = this
  },

  data () {
    return {
    }
  },

  methods: {
  }
}
</script>

<style lang="sass">
@import './css/app.sass'
</style>
