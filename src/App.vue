<template>
  <div id="app">
    <router-view />
    <div></div>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'

interface Foo {
  a: string
  b: string
}

export default Vue.extend({
  name: 'App'
})
</script>

<style lang="scss" scoped></style>
