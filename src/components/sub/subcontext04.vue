<template>
  <div class="main">
    <div class="top">
      <img style="" src="../../assets/init_pic/即将上线.png">
      <p>即将开通</p>
    </div>

    <h1> 即将开通</h1>
    <h4> 我们即将开通跨境物流、年度保税业务，可以帮您快速完成物流匹配，同时、也可以为您提供年度报税服务，以供您可以方便、快捷的完成报税</h4>

    <div class="pic">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/物流.png">
        <p>销售许可证</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/税.png">
        <p>销售许可证</p>
      </div>

    </div>
  </div>
</template>

<script>
  export default {
    name: "subcontext04"
  }
</script>

<style scoped lang="less">
  .top{
    margin: 0 50px;
    display: flex;
    align-items: center;
    >p{
      margin: 0 20px;
      font-size: 30px;
    }
    >img{
      width: 50px;
      height: 50px;
    }
  }
  .main{
    height: 350px;
  }
  .pic{
    height: 150px;
    >div{
      font-size: 14px;
      box-sizing: border-box;
      white-space: normal;
      word-wrap: break-word;
      word-break: break-all;
      overflow: hidden;
      display: inline-block;
      /*width: 200px;*/
      height: 100%;
      /*border: 10px solid red;*/
      margin: 20px;
      background-color: white;
    }
    >img{
      padding: 0 0 90px 0;
    }

  }
</style>