<script setup lang="ts">
import WujieVue from 'wujie-vue3'
</script>

<template>
  <div class="main">
    <WujieVue name="vue" width="50%" height="100%" url="http://localhost:777" />
    <WujieVue name="react" width="50%" height="100%" url="http://127.0.0.1:888" />
  </div>
</template>

<style scoped>
.main {
  display: flex;
}
</style>
