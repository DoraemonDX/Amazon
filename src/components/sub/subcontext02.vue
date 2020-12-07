<template>
  <div class="main">
    <div class="top">
      <img src="../../assets/init_pic/信用卡.png">
      <p>开美元账户</p>
    </div>
    <div>
      <p style="font-size: 30px">开立美国账户的好处</p>
    </div>


    <div class="main-box">
      <div class="sub-box">
        <div class="left box">
          <img src="../../assets/init_pic/购物车空.png">
        </div>
        <div class="right box">
          <p>可完成美国超过90%的消费，更加安全</p>
        </div>

      </div>
      <div class="sub-box">
        <div class="left box">
          <img src="../../assets/init_pic/定位.png">
        </div>
        <div class="right box">
          <p>方便美国购物、留学、旅游</p>
        </div>

      </div>
    </div>
    <div class="main-box">
      <div class="sub-box">
        <div class="left box">
          <img src="../../assets/init_pic/信用卡.png">
        </div>
        <div class="right box">
          <p>办理美国信用卡提前，累计信用积分</p>
        </div>

      </div>
      <div class="sub-box">
        <div class="left box">
          <img src="../../assets/init_pic/美元.png">
        </div>
        <div class="right box">
          <p>方便快过业务来往，规避外汇管制，合理避税</p>
        </div>

      </div>
    </div>


  </div>
</template>

<script>
  export default {
    name: "subcontext02"
  }
</script>

<style lang="less" scoped>
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
  .left{
    width: calc(30% - (20px) * 2);

  }
  .right{
    width: calc(70% - (20px) * 2);
  }
  .main-box{
    font-size: 30px;
    height: 150px;

  }
  .sub-box{
    display: flex;
    align-items: center;
    width: calc(50% - (20px) * 2);
    float: left;
    height: 100%;
    margin: 20px 20px;
  }
  .box{
    background-color: white;
    float: left;
    height: 100%;
    padding: 0px 10px;
    >img{
      width: 80px;
      height: 80px;
      margin-top: 30px
    }
    >p{

    }
  }

  .main{
    height: 600px;

  }

</style>