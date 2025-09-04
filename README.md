# vue--learning-journey
🚀关于这个仓库/n
这是我学习vue前端开发的日常记录与项目合集。<br>
目标：在七天内快速入门Vue，并通过实战项目不断提升。<br>
📅学习计划<br>
Day1 个人名片（Vue基础，ref，插值语法）<br>
<details>
  <summary>点击展开代码</summary>

```vue
<script setup>
import { ref } from 'vue'
const name = ref('小明')
const age = ref(20)
</script>

<template>
  <p>姓名：{{ name }}</p>
  <p>年龄：{{ age }}</p>
</template>
