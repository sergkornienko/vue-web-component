<template>
  <div>
    Vue component v2
    <p>{{name}}</p>
    <Nested count="3" />
  </div>
</template>

<script>
  import Nested from './Nested';
  export default {
    components: {
      Nested,
    },
    props: {
      name: {
        type: String,
        default: 'serhiiko',
      },
    }
  }
</script>