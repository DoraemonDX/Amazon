<template>
  <div>
    <div class="header">
      <div style="height: 150px; padding-top: 80px; font-size: 30px">
        <p>好卖网，帮你快速完成亚马逊商店</p>
      </div>
      <div>
        <h4>简单、快捷、亚马逊开店一站式服务</h4>
      </div>
    </div>

    <div class="pic context">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/注册公司.png">
        <p>公司注册</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/美国开户.png">
        <p>银行开户</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
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
        <img src="../../assets/init_pic/物流.png">
        <p>FBA物流</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/优化.png">
        <p>店铺优化</p>
      </div>
      <img src="../../assets/init_pic/箭头.png">
      <div style="display: inline-block;">
        <img src="../../assets/init_pic/税.png">
        <p>年度税报</p>
      </div>
    </div>

    <h1 style="color: #295888">马上咨询</h1>

  </div>
</template>

<script>
  export default {
    name: "subcontextheader"
  }
</script>

<style scoped lang="less">

  .context{
    margin: 50px 0;
  }
  .header{
    background-color: #295888;
    color: white;
    height: 350px;
    flex-direction:column;
    /*align-items: center;*/
  }
  .pic{

    height: 150px;
    >div{
      width: 100px;
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
      >img{
        width: 90px;
        height: 90px;

      }
    }
    >img{
      padding: 0 0 110px 0;


    }

  }

</style>