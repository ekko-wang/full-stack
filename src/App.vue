<template>
  <div id="app">
    <index/>
  </div>
</template>

<script>
import index from './components/index.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  methods:{
    test()  {
      var a = 10;
    }
  }
}
</script>

<style>

</style>
