<template>
  <h1>動態路由頁面: {{ $route.params.id }}</h1>
</template>

<script setup>

console.log('Dynamic route page loaded');
// 動態網址
// nuxt2: /pages/_id.vue
// nuxt3: /pages/[id].vue

const route = useRoute(); // auto imported 跟vue有關的api都可以直接使用
</script>
