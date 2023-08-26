<script setup lang="ts">

</script>

<template>
  <div class="choice-container">
    <div class="choice-title">400,000+用户值得信赖的选择</div>
    <div class="choice_wrapper">
      <div class="left">
        <div class="title1">
          “其他住宅代理网站”
        </div>

        <div class="list">
          <div class="item">昂贵的</div>
          <div class="item">操作困难</div>
          <div class="item">不安全且不稳定</div>
          <div class="item">……</div>
          <div class="item">位置覆盖差</div>
          <div class="item">客户服务响应缓慢</div>
        </div>
      </div>
      <div class="right">
        <div class="choice-right-title">代理</div>
        <div class="choice-right-title2">降低成本，提高效率</div>
        <div class="list">
          <div class="item">
            <div class="item-top">
              <div class="item-top-left-img"></div>
              <div class="item-top-right-img"></div>
            </div>
            <div class="item-title1">成功率</div>
          </div>

          <div class="item">
            <div class="item-top">
              <div class="item-top-left-img item-top-left-img2"></div>
              <div class="item-top-right-img"></div>
            </div>
            <div class="item-title1">地区</div>
          </div>

          <div class="item">
            <div class="item-top">
              <div class="item-top-left-img item-top-left-img3"></div>
              <div class="item-top-right-img"></div>
            </div>
            <div class="item-title1">速度</div>
          </div>

          <div class="item">
            <div class="item-top">
              <div class="item-top-left-img item-top-left-img4"></div>
              <div class="item-top-right-img"></div>
            </div>
            <div class="item-title1">价格</div>
          </div>
        </div>
      </div>
    </div>
    <div class="choice-btn">现在就开始</div>
  </div>
</template>

<style scoped>

.choice-container .choice_wrapper {
  width: 100%;
  height: 237px;
  position: relative;
  display: flex;
  align-items: flex-end;
  margin-top: 40px;
  margin-bottom: 40px;
}

.choice-container .choice_wrapper .right {
  position: absolute;
  right: 0;
  top: 0;
  width: 54%;
  margin-left: 300px;
  padding: 28px 54px;
  height: 217px;
  background: #fff;
  box-shadow: 0 2px 20px 0 rgba(35,42,136,.1);
  border-radius: 14px;
  border: 1px solid #e6e7eb;
  text-align: center;
  box-sizing: border-box;
}
.choice-container .choice-btn {
  width: 184px;
  line-height: 56px;
  background: #d8d8d8 linear-gradient(133deg,#0bcbc6,#10deac);
  box-shadow: 0 2px 8px 0 rgba(15,220,174,.24);
  border-radius: 35px;
  font-size: 18px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #fff;
  margin: 0 auto;
  cursor: pointer;
  border: none;
  text-align: center;
}
.choice-container .choice_wrapper .right .list {
  display: flex;
}
.choice-container .choice_wrapper .right .list .item {
  flex: 1;
}
.choice-container .choice_wrapper .right .list .item .item-title1 {
  font-size: 15px;
  font-family: PingFang SC-Medium;
  color: #929ca8;
  line-height: 16px;
  text-align: center;
}
.choice-container .choice_wrapper .right .list .item .item-top{
  display: flex;
  justify-content: center;
  margin-bottom: 8px;
}

.choice-container .choice_wrapper .right .list .item .item-top .item-top-left-img {
  width: 53px;
  height: 34px;
  background-image: url("static/png/num1.png");
  background-size: 54px 34px;
  margin-right: 4px;
}
.choice-container .choice_wrapper .right .list .item .item-top .item-top-left-img2 {
  width: 53px;
  height: 34px;
  background-image: url("static/png/num2.png");
  background-size: 54px 34px;
  margin-right: 4px;
}
.choice-container .choice_wrapper .right .list .item .item-top .item-top-left-img3 {
  width: 53px;
  height: 34px;
  background-image: url("static/png/num3.png");
  background-size: 54px 34px;
  margin-right: 4px;
}
.choice-container .choice_wrapper .right .list .item .item-top .item-top-left-img4 {
  width: 53px;
  height: 34px;
  background-image: url("static/png/num4.png");
  background-size: 54px 34px;
  margin-right: 4px;
}
.choice-container .choice_wrapper .right .list .item .item-top .item-top-right-img {
  width: 28px;
  height: 28px;
  background-image: url("static/png/up.png");
}

.choice-container .choice_wrapper .right .choice-right-title {
  font-size: 28px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 37px;
  margin-bottom: 11px;
}
.choice-container .choice_wrapper .right .choice-right-title2 {
  width: 100%;
  text-align: center;
  margin-bottom: 23px;
  color: #546577;
  font-size: 18px;
}


.choice-container .choice_wrapper .left {
  width: 50%;
  height: 176px;
  background: #f5f6fa;
  border-radius: 16px;
  border: 1px solid #e6e7eb;
  box-sizing: border-box;
  padding: 32px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.choice-container .choice_wrapper .left .list {
  display: flex;
  flex-wrap: wrap;
}
.choice-container .choice_wrapper .left .list .item {
  padding: 5px 10px 4px;
  background: #e0e0e7;
  border-radius: 3px;
  margin-bottom: 6px;
  flex-shrink: 0;
  margin-right: 6px;
  color: #77778e;
  font-size: 16px;
}
.choice-container .choice_wrapper .left .title1 {
  font-size: 20px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #526374;
  line-height: 26px;
  text-align: center;
}


.choice-container .choice-title {
  font-size: 36px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 47px;
  text-align: center;
  margin: 100px auto 0;
}
</style>
