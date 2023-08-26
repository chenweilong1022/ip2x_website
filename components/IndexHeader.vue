<script setup lang="ts">

</script>

<template>
  <div class="index-header-container">
    <div class="index-header-logo"></div>
    <div class="index-header-flex"></div>
    <div class="index-header-language"></div>
    <div class="index-header-english">English</div>
    <div class="index-header-more"></div>
    <div class="index-header-login">login</div>
    <div class="index-header-Sign">Sign Up</div>
  </div>
</template>

<style scoped>

.index-header-container {
  display: flex;
  align-items: center;
}

.index-header-logo {
  width: 133px;
  height: 38px;
  background-image: url("static/png/img_logob.png");
  background-size: 133px 38px;
}

.index-header-language {
  width: 26px;
  height: 26px;
  background-image: url("static/png/language.png");
  background-size: 26px 26px;
}

.index-header-more {
  width: 10px;
  height: 8px;
  background-image: url("static/png/ucenter_jt.png");
  background-size: 10px 8px;
}
.index-header-flex {
  flex: 1;
}
.index-header-english,.index-header-login,.index-header-Sign {
  height: 24px;
  line-height: 24px;
  font-size: 16px;
  font-weight: 600;
}
.index-header-english {
  margin: 0 10px;
}
.index-header-login {
  margin-left: 20px;
}
.index-header-Sign {
  width: 120px;
  height: 40px;
  background-color: #ffb331;
  line-height: 40px;
  text-align: center;
  border-radius: 20px;
  display: inline-block;
  box-sizing: border-box;
  margin-left: 20px;
  position: relative;
  color: white;
}

</style>
