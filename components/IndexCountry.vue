<script setup lang="ts">

</script>

<template>

  <div class="country-container">
    <div class="country-title">来自世界各地的住宅代理</div>
    <div class="country-sub-title">覆盖全球190多个国家和地区。超过6000万个活跃ip每天更新，99%的可用性</div>

    <div class="country-list">
      <div class="country-item" v-for="i in 8">
        <div class="country-logo">

        </div>
        <div class="country-item-right">
          <div class="country-item-right-title">加拿大</div>
          <div class="country-item-right-detail">518712+IPs</div>
        </div>
      </div>
    </div>

    <div class="btn_wrapper">
      <div class="btn_wrapper-btn">
        更多的位置
      </div>
      <div class="more">

      </div>
    </div>

  </div>
</template>

<style scoped>

.country-container .country-list {
  display: flex;
  flex-wrap: wrap;
  margin-top: 54px;
  margin-bottom: 34px;
}

.country-container .btn_wrapper {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #0acdc5;
  line-height: 24px;
  width: 228px;
  height: 56px;
  border-radius: 28px;
  border: 2px solid #0acdc5;
}

.country-container .btn_wrapper .btn_wrapper-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #0acdc5;
  line-height: 24px;
  width: 228px;
  height: 56px;
  border-radius: 28px;
  margin: 0 auto;
}

.country-container .btn_wrapper .more {
  width: 24px;
  height: 24px;
  border-radius: 56px;
  background: url(static/png/more.png) no-repeat 50%;
  background-size: cover;
}

.country-container .country-list .country-item {
  display: flex;
  width: 25%;
  padding-right: 20px;
  padding-bottom: 20px;
  box-sizing: border-box;
}

.country-container .country-list .country-item .country-logo {
  width: 56px;
  height: 56px;
  border-radius: 56px;
  background: url(static/png/us.svg) no-repeat 50%;
  background-size: cover;
  background-color: white;
}

.country-container .country-list .country-item .country-item-right {
  margin-left: 20px;
}

.country-container .country-list .country-item .country-item-right .country-item-right-title {
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #130f35;
  line-height: 24px;
  margin-bottom: 8px;
}
.country-container .country-list .country-item .country-item-right .country-item-right-detail {
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 24px;
}

.country-container .country-title {
  font-size: 36px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 47px;
  text-align: center;
}
.country-container .country-sub-title {
  margin-top: 16px;
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #929ca8;
  line-height: 24px;
  text-align: center;
}


</style>
