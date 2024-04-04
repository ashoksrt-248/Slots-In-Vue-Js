<template>
  <div>
    <h1> Card Component {{ content }}</h1>
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name:'Card',
    props:['content']
  }
</script>

<style scoped>

</style>