<script setup lang="ts">

</script>

<template>
  <div class="why-container">
    <div class="why-title">为什么要选择住宅代理平台?</div>
    <div class="why-list">
      <div class="why-item">
        <div class="why-item-padding">
          <div class="why-item-top"></div>
          <div class="why-item-title">
            专业的企业级服务
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>7*24小时服务支持，快速响应</div>
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>专属客户经理，贴心服务</div>
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>提供定制的解决方案</div>
          </div>
        </div>
        <div class="flex1"></div>
        <div class="why-item-bottom">
          <div class="line1">在线服务</div>
          <div class="line2">24小时</div>
        </div>
      </div>


      <div class="why-item">
        <div class="why-item-padding">
          <div class="why-item-top"></div>
          <div class="why-item-title">
            领先的行业技术
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>
              自主开发IP代理技术，运行稳定
            </div>
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>
              定期发现漏洞，签署并严格遵守保密协议
            </div>
          </div>


        </div>
        <div class="flex1"></div>
        <div class="why-item-bottom">
          <div class="line1">0.1秒</div>
          <div class="line2">快速反应</div>
        </div>
      </div>


      <div class="why-item">
        <div class="why-item-padding">
          <div class="why-item-top"></div>
          <div class="why-item-title">
            100%合规住宅
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>
              您的代理的来源必须符合道德标准并符合法规遵循标准。
            </div>
          </div>
          <div class="why_info">
            <div class="why_info-can">
            </div>
            <div>
              完全承诺遵守所有相关的数据保护法律要求
            </div>
          </div>
        </div>
        <div class="flex1"></div>
        <div class="why-item-bottom">
          <div class="line1">100%</div>
          <div class="line2">兼容的</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.why-container {
  margin-top: 100px;
}

.why-container .why-list {
  display: flex;
  justify-content: space-between;
  margin-top: 60px;
}

.why-container .why-list .why-item {
  width: 346px;
  height: 435px;
  background: #fff;
  box-shadow: 0 2px 20px 0 rgba(28,145,149,.09);
  border-radius: 8px;
  transition: all .3s linear;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.why-container .why-list .why-item .why-item-padding {
  padding: 40px 20px 0 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.why-container .why-list .flex1 {
  flex: 1;
}

.why-container .why-list .why-item .why-item-bottom {
  height: 100px;
  width: 100%;
  background: url(static/png/why_bg.png) no-repeat 50%;
  background-size: cover;
  padding-top: 20px;
}
.why-container .why-list .why-item .why-item-bottom .line1 {
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #fff;
  line-height: 24px;
  text-align: center;
}
.why-container .why-list .why-item .why-item-bottom .line2 {
  text-align: center;
  font-size: 22px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  line-height: 29px;
  margin-bottom: 4px;
}

.why-container .why-list .why-item .why_info {
  display: flex;
  align-items: flex-start;
  margin-bottom: 12px;
}

.why-container .why-list .why-item .why_info .why_info-can {
  width: 20px;
  height: 20px;
  border-radius: 20px;
  background: url(static/png/right_can.png) no-repeat 50%;
  background-size: cover;
  margin-right: 6px;
}

.why-container .why-list .why-item .why-item-title {
  margin: 20px 28px 24px;
  font-size: 20px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 26px;
  text-align: center;
}

.why-container .why-list .why-item .why-item-top {
  width: 68px;
  height: 68px;
  border-radius: 68px;
  background: url(static/png/why_icon1.png) no-repeat 50%;
  background-size: cover;
}

.why-container .why-title {
  font-size: 36px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 47px;
  text-align: center;
}
</style>
