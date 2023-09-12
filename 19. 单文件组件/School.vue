<template>
  <!-- 组件的结构 -->
  <div id="demo">
    <div> {{ schName }}</div>
  </div>
</template>

<script>
  // 组件交互相关的代码（数据，方法）

  // 完整写法
  // export default Vue.extend({
  //   data() {
  //     return {
  //       schName: 'school'
  //     }
  //   }
  // })

  // 缩写
  export default {
    // 设置组件名
    name: "School",
    data() {
      return {
        schName: 'school'
      }
    }
  }

</script>

<style>
  /* 组件的样式 */

  #demo {
    background-color: yellow;
  }
</style>
