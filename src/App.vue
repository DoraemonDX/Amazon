<template>
  <div id="app">

    <el-container>
      <el-header>
        <Top></Top>
      </el-header>
      <el-main>
        <subcontextheader></subcontextheader>
        <subcontext title="注册公司"></subcontext>
        <subcontext02></subcontext02>
        <subcontext03></subcontext03>
        <subcontext04></subcontext04>
      </el-main>

      <el-footer>
        <Buttom></Buttom>
      </el-footer>
    </el-container>


  </div>
</template>

<script>

import subcontext from "./components/sub/subcontext";
import Subcontext02 from "./components/sub/subcontext02";
import Subcontext03 from "./components/sub/subcontext03";
import Subcontext04 from "./components/sub/subcontext04";
import Subcontextheader from "./components/sub/subcontextheader";
import Top from "./components/sub/top";
import Buttom from "./components/sub/buttom";


export default {
  name: 'app',
  components: {
    Buttom,
    Top,
    Subcontextheader,
    Subcontext04,
    Subcontext03,
    Subcontext02,
    subcontext,

  }
}
</script>

<style lang="less" scoped>
#app {
  text-align: center;
}
</style>
