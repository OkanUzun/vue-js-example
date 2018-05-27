<template>
  <div>
    <h1>{{message}} {{firstName}} {{lastName}}</h1>
  </div>
</template>

<script>
  export default {
    name: 'Example',
    data () {
      return {
        message: 'Hello',
        firstName: 'Okan',
        lastName: 'Uzun'
      }
    }
  }
</script>

<style scoped>

</style>
