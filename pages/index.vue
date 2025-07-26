<template>
    <h1>首頁</h1>
    <Todo />
    <Card />
    <CardPhoto />
    - component內不叫index.vue的組件，引入時必須加上資料夾前綴
    - 不想要前綴的話需另外import(老方法)
</template>

<script setup>
console.log('Index page loaded');
</script>