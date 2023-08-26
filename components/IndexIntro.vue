<script setup lang="ts">

</script>

<template>
  <div class="intro-container">
    <div class="intro-item">
      <div class="item-bgc"></div>
      <div class="item-title1">稳定高效</div>
      <div class="item-title2">丰富的带宽支持业务需求。99%的成功率保证数据收集活动。</div>
    </div>
    <div class="intro-item">
      <div class="item-bgc item-bgc2"></div>
      <div class="item-title1">无限的会话</div>
      <div class="item-title2">代理的使用次数或调用频率没有限制</div>
    </div>
    <div class="intro-item">
      <div class="item-bgc item-bgc3"></div>
      <div class="item-title1">操作方便</div>
      <div class="item-title2">通过用户名和密码认证的方式生成代理，方便快捷。</div>
    </div>
    <div class="intro-item">
      <div class="item-bgc item-bgc4"></div>
      <div class="item-title1">安全匿名</div>
      <div class="item-title2">获得高度匿名的真实住宅ip，完全保护您的隐私安全。</div>
    </div>
  </div>
</template>

<style scoped>

.intro-container {
  display: flex;
  justify-content: space-between;

  background: #f5f6fa;
  border-radius: 12px;
  align-items: center;
  flex-wrap: nowrap;
  flex-direction: row;
  margin-top: 20px;
}
.intro-container .intro-item {
  width: 300px;
  height: 324px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 0 24px;
}

.intro-container .intro-item .item-bgc {
  width: 140px;
  height: 84px;
  background-image: url("static/png/intro1.png");
  background-size: 140px 84px;
  margin: 0 auto;
}
.intro-container .intro-item .item-bgc2 {
  width: 140px;
  height: 84px;
  background-image: url("static/png/intro2.png");
  background-size: 140px 84px;
  margin: 0 auto;
}
.intro-container .intro-item .item-bgc3 {
  width: 140px;
  height: 84px;
  background-image: url("static/png/intro3.png");
  background-size: 140px 84px;
  margin: 0 auto;
}
.intro-container .intro-item .item-bgc4 {
  width: 140px;
  height: 84px;
  background-image: url("static/png/intro4.png");
  background-size: 140px 84px;
  margin: 0 auto;
}

.intro-container .intro-item .item-title1 {
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 24px;
  text-align: center;
  margin: 16px auto;
}

.intro-container .intro-item .item-title2 {
  font-size: 15px;
  font-family: PingFang SC-Medium;
  color: #929ca8;
  line-height: 20px;
  text-align: center;
}
</style>
