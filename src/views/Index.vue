<template>
  <div>
    <h1>嘎嘎</h1>
    <el-button @click="showMsg" type="primary">按钮</el-button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        text: "嘎嘎嘎嘎"
      }
    },
    methods: {
      showMsg() {
        this.$message({
          type: "success",
          message: this.text
        })
      }
    }
  }
</script>
