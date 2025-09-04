# vue--learning-journey
🚀关于这个仓库/n
这是我学习vue前端开发的日常记录与项目合集。<br>
目标：在七天内快速入门Vue，并通过实战项目不断提升。<br>
📅学习计划<br>
Day1 个人名片（Vue基础，ref，插值语法）<br>
vue<br>
<script setup><br>
import { ref } from 'vue'  <!-- 导入 Vue3 响应式 API --><br>

const name = ref('小明')  <!-- 响应式变量 name --><br>
const age = ref(20)       <!-- 响应式变量 age --><br>
</script><br>

<template><br>
  <p>姓名：{{ name }}</p>  <!-- 显示 name --><br>
  <p>年龄：{{ age }}</p>   <!-- 显示 age --><br>
</template><br>
