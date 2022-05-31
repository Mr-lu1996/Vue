<template>
  <div>
      <h2>学生信息</h2>
      <h3>学生姓名：{{name}}</h3>
      <h3>学生年龄：{{age}}</h3>
  </div>
</template>

<script>
    export default {
        name: 'Student',
        data() {
            return {
                name: '鹿先森',
                age: 18
            }
        }
    }
</script>

<style>

</style>