<template>
  <div class="container">
    <comp-validate></comp-validate>
  </div>
</template>

<script>
import compvalidate from './components/validate'

export default{
  components: {

    compvalidate 
  }
}
</script>
<style scoped>
.container{
  background-color: blue;
}
</style>
