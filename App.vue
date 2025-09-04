<template>
  <div id="app">
    <h1>{{ name }}</h1>
    <p>职业：{{ job }}</p>
    <p>邮箱：{{ email }}</p>
    <p>个人介绍：{{ intro }}</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const name = ref('张三')
const job = ref('学生')                // 注意这里是变量
const email = ref('56814375pyh@gmail.com') // 直接字符串赋值，不加 <src>
const intro = ref('希望财富自由')      // 变量
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}

h1 {
  color: #42b983;
}
</style>
