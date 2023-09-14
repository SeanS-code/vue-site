<script setup>
import Navigation from './views/navigation.vue'
import Welcome from './views/welcome.vue'
import ToDo from './views/todo.vue'
import Entries from './views/entries.vue'
import Schedule from './views/schedule.vue'
import Footing from './views/footer.vue'
</script>

<template>
  <div id="app">
    <Navigation />

    <Welcome />

    <ToDo />

    <Entries />

    <Schedule />

    <Footing />
  </div>
</template>

<script>

export default {

}
</script>

<style scoped>
@media (min-width: 1024px) {}
</style>
