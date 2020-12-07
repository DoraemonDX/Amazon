<template>
  <div class="sub-context">

    <div class="top">
        <img style="display: block" src="../../assets/init_pic/注册公司.png">
        <p>注册公司</p>
    </div>

    <h1>为什么要注册美国公司</h1>
    <div class="sub-box">
      <div class="box">
        <div class="left mini-box">
          <p>国际品牌</p>
        </div>
        <div class="right mini-box">
          <p>美国企业在世界各地的市场上有着实力雄厚，技术先进以及作风诚信的形象，注册成立美国公式是企业开展跨国业务，提升企业国际印象的最优选择</p>
        </div>
      </div>
      <div class="box" >
        <div class="left mini-box">
          <p>跨境电商</p>
        </div>
        <div class="right mini-box">
          <p>亚马逊作为美国本土企业，对美国公司注册的账号在封号、促销等政策上有一定的照顾，平台的消费者更信赖美国公司的产品，对销量的提升有一定的帮助</p>
        </div>
      </div>
    </div>
    <div class="sub-box">
      <div class="box" >
        <div class="left mini-box">
          <p>实地经营</p>
        </div>
        <div class="right mini-box">
          <p>美国市场获得越来越关注，注册美国公司是成为真正的国际企业的最快捷方式，还可以让企业合理避税，摆脱外汇管制等众多便利</p>
        </div>
      </div>
      <div class="box" >
        <div class="left mini-box">
          <p>移民签证</p>
        </div>
        <div class="right mini-box">
          <p>注册美国公司提供赴美商务活动的机会，极大的方便了赴美签证、子女留学、亲友担保、组团商务考察、为您全家移民扫除障碍</p>
        </div>
      </div>
    </div>

    <h1>公司后续维护</h1>
    <h4>根据您的需要您对公司做公司变更和公司注销业务</h4>

    <div class="btm-pic">
      <img src="../../assets/init_pic/公司变更.png">
      <img src="../../assets/init_pic/注销公司.png">
    </div>
  </div>
</template>

<script>
  export default {
    name: "subcontext",
    props: ['title'],
  }
</script>

<style scoped lang="less">
  .btm-pic{
    margin-top: 40px;
    >img{
      width: 150px;
      height: 180px;
      margin: 0 150px;
    }
  }
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
  .sub-context {
    background-color: #fafafb;
  }
  .mini-box {
    background-color: white;
    float: left;
    height: 100%;
    padding: 0px 20px;
    display: flex;
    align-items: center;
  }
  .left {
    width: calc(30% - (20px) * 2);
    font-size: 50px;
  }
  .right {
    width: calc(70% - (20px) * 2);
    font-size: 25px;

  }
  .sub-box {
    width: 100%;
    height: 200px;

  }
  .box {
    width: calc(50% - (30px) * 2);
    float: left;
    height: 100%;
    padding: 20px 30px;

  }


</style>