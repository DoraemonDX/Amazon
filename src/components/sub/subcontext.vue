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
          <p>而非弄二五年佛文革哦i日内瓦狗肉i能够女偶尔能够未能够而亡 飞鸟</p>
        </div>
      </div>
      <div class="box" >
        <div class="left mini-box">
          <p>跨境电商</p>
        </div>
        <div class="right mini-box">
          <p>而非弄二五年佛文革哦i日内瓦狗肉i能够女偶尔能够未能够而亡 飞鸟</p>
        </div>
      </div>
    </div>
    <div class="sub-box">
      <div class="box" >
        <div class="left mini-box">
          <p>实地经营</p>
        </div>
        <div class="right mini-box">
          <p>而非弄二五年佛文革哦i日内瓦狗肉i能够女偶尔能够未能够而亡 飞鸟</p>
        </div>
      </div>
      <div class="box" >
        <div class="left mini-box">
          <p>移民签证</p>
        </div>
        <div class="right mini-box">
          <p>而非弄二五年佛文革哦i日内瓦狗肉i能够女偶尔能够未能够而亡 飞鸟</p>
        </div>
      </div>
    </div>

    <h1>公司后续维护</h1>
    <h4>贡藕四大佛恩哦i能够而亡哦i谁能给我能够i都认为的是妇科阿公i俄国</h4>

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