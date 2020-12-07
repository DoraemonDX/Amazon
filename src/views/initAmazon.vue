<template>
  <div class="init_amazon">
    <init-context></init-context>
  </div>
</template>

<script>

  import top from './Top'
  import initContext from "../components/initContext";

  export default {
    name: "init_Amazon",
    components: {top,initContext},
  }
</script>

<style scoped lang="less">
  .init_amazon{
    height: 100%;
  }
</style>