<script setup lang="ts">

</script>

<template>
  <div class="advantage-container">
    <div class="advantage-title">代理的优势</div>
    <div class="advantage_wrapper">
      <div class="left">

      </div>
      <div class="right">
        <div class="right-header">
          通过我们的代理，您可以获得高延迟，绝对准确性，全球220多个地区的60M+ ip，快速响应和无限并发请求。
        </div>

        <div class="right-body">
          <div class="item">
            <div class="title">超高的并发</div>
            <div class="detail">专用高性能服务器以真实居住地址请求访问，维护代理的正常连接。</div>
          </div>

          <div class="item">
            <div class="title">优质IP资源</div>
            <div class="detail">
              在PROXY IP池中收集60M+真实住宅IP。
            </div>
          </div>

          <div class="item">
            <div class="title">用户和通行证授权</div>
            <div class="detail">支持多个代理用户。</div>
          </div>

          <div class="item">
            <div class="title">自定义服务</div>
            <div class="detail">支持根据场景定制专属IP代理方案。</div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>

.advantage-container {
  margin-top: 100px;
}

.advantage-container .advantage-title {
  margin-bottom: 40px;
}

.advantage-container .advantage_wrapper .right .right-header {
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #526374;
  line-height: 24px;
  margin-bottom: 20px;
  text-align: left;
}

.advantage-container .advantage_wrapper .right .right-body .item {
  width: 649px;
  transition: all .2s linear;
  background: #f5f5f7;
  border-radius: 10px;
  padding: 20px 24px;
  text-align: left;
  margin-bottom: 8px;
}
.advantage-container .advantage_wrapper .right .right-body .item .title {
  transition: all .2s linear;
  font-size: 20px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 26px;
}
.advantage-container .advantage_wrapper .right .right-body .item .detail {
  transition: all .2s linear;
  font-size: 18px;
  font-family: PingFang SC-Medium;
  color: #929ca8;
  line-height: 24px;
  margin: 16px 0 20px;
}

.advantage-container .advantage_wrapper {
  display: flex;
}
.advantage-container .advantage_wrapper .left {
  width: 586px;
  height: 616px;
  background-image: url("static/png/vda.png");
  background-size: 586px 616px;
  margin-right: 80px;
}
.advantage-container .advantage-title {
  font-size: 36px;
  font-family: PingFang SC-Medium,PingFang SC-Regular;
  font-weight: 700;
  color: #130f35;
  line-height: 47px;
  text-align: center;
}

</style>
