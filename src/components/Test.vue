<template lang="pug">
  .test
    span hello
</template>

<style scoped lang="stylus">
</style>

<script lang="ts">
  import {
    Component, Prop, Vue,
  } from 'vue-property-decorator'

  @Component
  export default class Test extends Vue {

  }
</script>
