<script setup>
</script>

<template>
  <div style="text-align: center; padding: 50px; font-family: Arial">
    <h1>Lab 07: Automated Deployment</h1>
    <h2>你的名字</h2>
    <p>学号：你的学号</p>
    <p>这个页面是通过 GitHub Actions 自动部署的 🚀</p>
    <p>部署时间：{{ new Date().toLocaleString() }}</p>
  </div>
</template>

<style scoped>
h1 { color: #42b883; }
h2 { color: #35495e; }
</style>
