<template>
<!--  <Tutorial/>-->
<div class="home-container">
  <div class="home-p200-container">
    <IndexHeader></IndexHeader>
    <IndexBanner></IndexBanner>
    <IndexIntro></IndexIntro>
    <IndexGd></IndexGd>
    <IndexChoice></IndexChoice>
    <IndexAdvantage></IndexAdvantage>
  </div>
  <IndexAs></IndexAs>
  <IndexBusiness></IndexBusiness>
  <IndexCountry></IndexCountry>
  <IndexWhy></IndexWhy>

  <IndexFaq></IndexFaq>
  <IndexContact></IndexContact>

  <div class="footer-container">
    <div class="logo"></div>
    <div class="content">

      <div class="footer-list">
        <div class="footer-item">
          <div class="footer-item-h">服务</div>
          <div class="footer-item-detail">定价</div>
          <div class="footer-item-detail">应用场景</div>
          <div class="footer-item-detail">帮助中心</div>
          <div class="footer-item-detail">博客</div>
          <div class="footer-item-detail">关于我们</div>
        </div>
      </div>

      <div class="footer-list">
        <div class="footer-item">
          <div class="footer-item-h">最高位置</div>
          <div class="footer-item-detail">美国</div>
          <div class="footer-item-detail">英国</div>
          <div class="footer-item-detail">加拿大</div>
          <div class="footer-item-detail">德国</div>
          <div class="footer-item-detail">所有的位置</div>
        </div>
      </div>

      <div class="footer-list">
        <div class="footer-item">
          <div class="footer-item-h">常规</div>
          <div class="footer-item-detail">联盟计划</div>
          <div class="footer-item-detail">代理检查程序</div>
          <div class="footer-item-detail">免费代理列表</div>
          <div class="footer-item-detail">ISP代理</div>
        </div>
      </div>

      <div class="footer-list">
        <div class="footer-item">
          <div class="footer-item-h">即时消息</div>
          <div class="footer-item-detail">ip2worldProxy@outlook.com</div>
        </div>
      </div>

    </div>

  </div>

</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})

</script>


<style>

*{
  margin:0;
  padding:0
}
li{
  list-style:none
}
img{
  vertical-align:top;
  border:none
}
</style>

<style scoped>

.home-container .home-p200-container {
  padding: 21px 200px;
}

.footer-container {
  width: 100%;
  background: #130f35;
  padding: 48px 58px;
  box-sizing: border-box;
}

.footer-container .content {
  display: flex;
}

.footer-container .content .footer-list {
  margin-top: 48px;
  flex: 1;
}

.footer-container .content .footer-list .footer-item .footer-item-h {
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  line-height: 24px;
  margin-bottom: 20px;
}

.footer-container .content .footer-list .footer-item .footer-item-detail {
  color: #677188;
  line-height: 26px;
  cursor: pointer;
  margin-bottom: 20px;
}

.footer-container .logo {
  width: 154px;
  height: 44px;
  background: url(static/png/logo2.png) no-repeat 50%;
  background-size: cover;
}

</style>
