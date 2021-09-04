<template>
  <div id="app">
    <router-view />
    <p class="text">hello word</p>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'App'
})
</script>

<style lang="scss" scoped>

.text {
  color: $success-color;
}
</style>
