<template>
  <div id="app">
    fkflasfklasfklaskflkaslfklkasfklsfk
  </div>
</template>

<script>
import HomePage from './components/HomePage'
import MenuPage from './components/MenuPage'

export default {
  name: 'app',
  data () {
    return {
      menuIsOpen: false
    }
  },
  components: {
    HomePage,
    MenuPage
  },
    mounted() {
      alert(window.cordova);
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ons-splitter-side[side=left][animation=overlay] {
  border-right: 1px solid #BBB;
}
</style>
