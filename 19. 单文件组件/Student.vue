<template>
  <!-- 组件的结构 -->
  <div>
    <div> {{ stuName }}</div>
  </div>
</template>

<script>
  export default {
    // 设置组件名
    name: "School",
    data() {
      return {
        stuName: 'student'
      }
    }
  }

</script>
