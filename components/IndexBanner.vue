<script setup lang="ts">

</script>

<template>
  <div class="banner-container">
    <div class="banner-left-container">
      <div class="title1">可用资源</div>
      <div class="title2">
        全球高质量住宅代理平台
      </div>
      <div class="title3">
        在全球190+的国家和城市级别的地区拥有60M+个ip
      </div>
      <div class="btn">
        现在就开始
      </div>
    </div>
    <div class="banner-right-container">
    </div>
  </div>
</template>

<style scoped>

.banner-container {
  margin-top: 56px;
  display: flex;
  justify-content: space-between;
}
.banner-left-container .title1 {
  font-size: 20px;
  color: #0acdc5;
  line-height: 26px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
}
.banner-left-container .title2 {
  font-size: 48px;
  font-family: 'Outfit-ExtraBold';
  line-height: 60px;
  color: #091c40;
  width: 459px;
  padding-top: 30px;
  font-weight: bold;
}
.banner-left-container .title3 {
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #526374;
  line-height: 26px;
  margin-top: 22px;
  margin-bottom: 48px;
}
.banner-left-container .btn {
  display: inline-block;
  width: 178px;
  height: 48px;
  line-height: 48px;
  text-align: center;
  background: #d8d8d8 linear-gradient(133deg,#0bcbc6,#10deac);
  border-radius: 8px;
  font-size: 20px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
}

.banner-right-container {
  width: 545px;
  height: 374px;
  background-image: url("static/png/banner_right.png");
  background-size: 545px 374px;
}
</style>
