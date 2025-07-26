<template>
  <div>
    <h1>待辦事項</h1>
    <ul>
      <li v-for="todo in todos" :key="todo.id">{{ todo.text }}</li>
    </ul>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const todos = ref([
  { id: 1, text: '學習 Vue 3' },
  { id: 2, text: '學習 Nuxt 3' },
  { id: 3, text: '建立一個 Todo 應用程式' }
]);
</script>

<style scoped>
h1 {
  font-size: 2em;
  margin-bottom: 0.5em;
}
</style>
