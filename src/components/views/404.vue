<template>
  <a-row>
    <a-col :span="8" class="left-area">
      <div class="white-font-left">Not Found<br>404</div>
    </a-col>
    <a-col :span="16" class="right-area">
      <div class="white-font-right">
        <!-- TODO 这部分肯定记得优化下 -->
        <div>我喜欢你，喜欢的不得了，不管你对我做了什么我都不会变得讨厌你的哦？<br>—— 小木曾雪菜</div>
      </div>
    </a-col>
  </a-row>
</template>

<script>

export default {
  name: "404"
}
</script>

<style scoped>
* {
  height: 100%;
  box-sizing: inherit;
}

.left-area {
  background-color: #AD4E00;
  height: 100%;
  transition: width 0.28s;
  position: fixed; /*根据高度撑满*/
  /*font-size: 0px;*/
  top: 0;
  bottom: 0;
  left: 0;
  z-index: 1001;
  overflow: hidden;
}

.right-area {
  background: #FFF;
  position: fixed; /*根据高度撑满*/
  margin-left: calc(100% * (1/3));
}

.white-font-left {
  color: #FFF;
  background: #AD4E00;
  height: 100%;
  font-family: 'JetBrains Mono', serif;
  padding-left: 55px;
  padding-top: 50px;
  font-size: 65px;
}

.white-font-right {
  background: #FFF;
  height: 100%;
  font-family: 'JetBrains Mono', 'Microsoft YaHei', serif;
  float: right;
  padding-right: calc(100% * (1/6));
  padding-top: calc(100% * (3/5));
  font-size: 25px;
}
</style>
