<script setup lang="ts">

</script>

<template>
  <div class="contact-contianer">
    <div class="left">
      <div class="ready">你准备好出发了吗?</div>
      <div class="det">
        立即开始，或联系我们的售前顾问之一，了解代理如何帮助您或您的团队改进。
      </div>
    </div>
    <div style="width: 173px"></div>
    <div class="right">
      <div class="start_btn">现在就开始</div>
      <div class="talk_btn">与销售人员交谈</div>
    </div>

  </div>
</template>

<style scoped>

.contact-contianer {
  margin-top: 100px;
  width: 100%;
  height: 240px;
  background: url(static/png/contact.png) no-repeat 50%;
  background-size: cover;
  display: flex;
  justify-content: center;
  padding-top: 50px;
  justify-content: center;
  align-items: center;
}

.contact-contianer .right .start_btn {
  width: 146px;
  height: 48px;
  background: #fff;
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #0acdc5;
  line-height: 48px;
  text-align: center;
  border-radius: 9px;
  margin-right: 16px;
  transition: all .3s linear;
}

.contact-contianer .right {
  display: flex;
  margin-right: 16px;
}

.contact-contianer .right .talk_btn {
  width: 146px;
  height: 48px;
  background: hsla(0,0%,100%,.2);
  border-radius: 9px;
  border: 1px solid #fff;
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  line-height: 48px;
  text-align: center;
  transition: all .3s linear;
}



.contact-contianer .left .ready {
  font-size: 38px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  line-height: 50px;
  margin-bottom: 20px;
}

.contact-contianer .left .det {
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #fff;
  line-height: 24px;
  width: 480px;
}

</style>
