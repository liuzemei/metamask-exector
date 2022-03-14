<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
import { NLoadingBarProvider } from 'naive-ui'
</script>

<template>
  <n-loading-bar-provider class="app">
    <HelloWorld />
  </n-loading-bar-provider>
</template>

<style>
* {
  padding: 0;
  margin: 0;
}

#app {
  margin: 20px;
}
</style>