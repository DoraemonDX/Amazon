<template>

<!-- 最顶上的样式 -->
  <div>
    <div class="Top">
      <div>
        {{left}}
      </div>
      <div>{{}}</div>
      <div>12</div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Top",
    props:['left'],
  }
</script>

<style lang="less" scoped>
  .Top{
    height: 45px;
    background-color: #000000;
    display: flex;
    div{
      flex:1;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 20px;
      color: #ffffff;
    }
  }
</style>