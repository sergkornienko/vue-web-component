<template>
  <p>nested {{count}}</p>
</template>

<script>
  export default {
    name: 'Nested',
    props: {
      count: {
        type: Number,
        default: 0,
      },
    }
  }
</script>