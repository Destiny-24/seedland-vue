<template>
  <div id="app">
    <Index />
  </div>
</template>

<script>
import Index from './components/index.vue'
export default {
  name: 'app',
  components: {
    Index
  }
}
</script>

<style  lang="less">
*{
  font-family:fantasy;
  margin: 0;
  box-sizing: border-box;
}
</style>