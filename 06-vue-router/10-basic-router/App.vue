<script setup lang="ts">
import { MeetupsFooter } from '@shgk/vue-course-ui'
import MeetupsHeader from './components/MeetupsHeader.vue'
import PageIndex from './views/PageIndex.vue'
/*  <PageIndex /> */
</script>

<template>
  <div class="wrapper">
    <MeetupsHeader />
    <main class="main">
      <RouterView />
    </main>
    <MeetupsFooter />
  </div>
</template>

<style scoped>
.wrapper {
  background-color: var(--color-bg-plain);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.main {
  flex: 1 0 auto;
}
</style>
