<template>
  <div class="top">
    <img v-bind:src="src">
    <p>{{text}}</p>
  </div>
</template>

<script>



  export default {
    name: "sub-top",
    props:[
        "src",
        "text",
    ]
  }
</script>

<style scoped lang="less">
  .top{
    display: flex;
    align-items: center;
    >img{
      width: 90px;
      height: 90px;
    }
  }

</style>