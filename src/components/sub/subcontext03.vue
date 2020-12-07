<template>
  <div class="main">
    <div class="top">
      <img src="../../assets/init_pic/开店.png">
      <p>店铺运营</p>
    </div>

    <h1>店铺运营</h1>
    <h4>我们可以帮助您完成经营许可证申请、亚马逊开店已经店铺优化的工作、帮助您快速上架以及店铺优化、以帮助您完成快速商品销售</h4>

    <div class="pic">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/销售许可证.png">
        <p>经营许可证</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/开店.png">
        <p>亚马逊开店</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/优化.png">
        <p>店铺优化</p>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: "subcontext03"
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
  .main{
    background-color:#fafafb ;
    height: 450px;
  }

</style>
