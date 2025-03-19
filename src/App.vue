<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <main>
    <div class="wrapper">
      <HelloWorld />
    </div>
  </main>
</template>

<style scoped>

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }
   .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
