<template>
  <div id="app">
    <landing></landing>
  </div>
</template>

<script>
import Landing from './components/Landing.vue';
export default {
  name: 'app',
  data () {
    return {

    }
  },
  components: {
    'landing': Landing
  }
}
</script>

<style lang="scss">

</style>
