<template>
<!--  图片+名字-->
  <div class="sub_image">
    <div class="avatar_box">
      <img src="../../assets/init_pic/注册公司.png">
      <div>
        <span>{{context_01}}</span>
      </div>
    </div>
    <div class="title">
      <span>{{title}}</span>
    </div>
    <el-card class="box-card text item">
      <el-row>
        <el-col :span = "7">
          <div class="box-card-left">
            <span>国际品牌</span>
          </div>
        </el-col>
        <el-col :span = "17">
          <div class="box-card-right">
            <span>狗儿万能公式 拍那个破让你公司能否呢婆娘我更困难的批能够剖</span>
          </div>
        </el-col>
      </el-row>
    </el-card>
    <el-card class="box-card text item">
      <el-row>
        <el-col :span = "7">
          <div class="box-card-left">
            <span>国际品牌</span>
          </div>
        </el-col>
        <el-col :span = "10">
          <div class="box-card-right">
            <span>狗儿万能公式 拍那个破让你公司能否呢婆娘我更困难的批能够剖</span>
          </div>
        </el-col>
      </el-row>
    </el-card>

    <el-card class="box-card">
      <div slot="header" class="clearfix">
        <span>卡片名称</span>
        <el-button style="float: right; padding: 3px 0" type="text">操作按钮</el-button>
      </div>
      <div v-for="o in 4" :key="o" class="text item">
        {{'列表内容 ' + o }}
      </div>
    </el-card>




  </div>
</template>

<script>
  export default {
    name: "subimage",
    props:['context_01','title'],
  }
</script>

<style scoped lang="less">

  /*.text {*/
  /*  font-size: 14px;*/
  /*}*/

  .item {
    padding: 18px 0;
  }

  .box-card {
    height: 100%;
    flex-wrap: nowrap;
    margin: 15px;
    background-color: white;
    width: 45%;
    float: left;
    .box-card-left{
      font-size: 20px;

      margin-right: 5px;
    }
    .box-card-right{
    }
    .el-row{
      flex-wrap: nowrap;
      padding-left: 6px;
      float: left;
    }
    .el-col{
      float: left;
    }
  }

  .title{
    color: black;
    font-size: 30px;
  }

  .sub_image{
    background-color: #42b983;
    height: 100%;
  }

  .avatar_box{
    > div{
      display: flex;
      align-items: center;
      span{
        margin-left: 15px;
        word-break:keep-all;
      }
    }
    display: flex;
    vertical-align:middle;
    height: 50px;
    width: 50px;
    img{
      width: 100%;
      height: 100%;
    }
  }
</style>