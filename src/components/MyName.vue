<script setup>
const studentName = 'Zhengwu Yue'
const unitCode = 'FIT5032'
</script>

<template>
  <section class="my-name">
    <h2>My name is {{ studentName }}</h2>
    <p>Welcome to my {{ unitCode }} Vue.js application.</p>
  </section>
</template>

<style scoped>
.my-name {
  margin-top: 24px;
  padding: 20px;
  border: 1px solid #cccccc;
  border-radius: 8px;
}

.my-name h2 {
  margin: 0 0 8px;
  color: #2c3e50;
}

.my-name p {
  margin: 0;
}
</style>
