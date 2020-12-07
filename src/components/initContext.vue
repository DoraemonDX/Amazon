<template>
  <div class="initContext">
    <sub-image  context_01="注册公司" title="为什么注册美国公司"></sub-image>
  </div>
</template>

<script>
  import subImage from "./sub/subimage";
  export default {
    name: "init_context",
    components: {subImage},
  }
</script>

<style scoped lang="less">
  .initContext{
    height: 100%;
    /*background-color: azure;*/
  }
</style>