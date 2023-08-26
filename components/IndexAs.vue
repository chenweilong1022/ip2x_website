<script setup lang="ts">

</script>

<template>

  <div class="as-container">
    <div class="title">应用场景</div>
    <div class="list">
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">电子商务</div>
          <div class="detail">全面洞察市场和竞争对手信息，领先一步。</div>
        </div>
      </div>
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">搜索引擎优化监测</div>
          <div class="detail">收集和分析serp数据，优化你的SEO策略，排名高于竞争对手。</div>
        </div>
      </div>
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">品牌保护</div>
          <div class="detail">
            通过维护品牌资产和广告验证，打击品牌侵权和品牌老化。
          </div>
        </div>
      </div>
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">社交媒体管理</div>
          <div class="detail">
            最大限度地发挥品牌影响力，触及品牌合理距离之外的潜在客户。
          </div>
        </div>
      </div>
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">市场研究</div>
          <div class="detail">在进入你的目标市场之前，要像了解你的手背一样了解它。</div>
        </div>
      </div>
      <div class="as-list-item">
        <div class="logo"></div>
        <div class="right">
          <div class="as-right-title">网页抓取</div>
          <div class="detail">启用网页抓取/爬虫上网冲浪免费的IP块和验证码。</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>


.as-container {
  width: 100%;
  height: 628px;
  background: url(static/png/as_bg.png) no-repeat 50%;
  background-size: cover;
  background-color: white;

}

.as-container .title {
  font-size: 36px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  line-height: 47px;
  padding-top: 80px;
  text-align: center;
  margin-bottom: 49px;
}

.as-container .list {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.as-container .list .as-list-item {
  width: 49%;
  height: 120px;
  background: #fff;
  border-radius: 4px;
  margin-bottom: 20px;
  display: flex;
  padding: 22px 26px;
  transition: all .3s linear;
  box-sizing: border-box;
}
.as-container .list .as-list-item {
  display: flex;
  align-items: center;
}
.as-container .list .as-list-item .logo {
  width: 60px;
  height: 60px;
  background: url(static/png/scene1.png) no-repeat 50%;
  background-size: cover;
  margin-right: 26px;
}
.as-container .list .as-list-item .right .as-right-title {
  font-size: 20px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 26px;
  margin-bottom: 8px;
  text-align: center;
}
.as-container .list .as-list-item .right .detail {
  font-size: 16px;
  font-family: PingFang SC-Medium;
  color: #929ca8;
  line-height: 21px;
  text-align: center;
}
</style>
