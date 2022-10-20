<template>
  <div class="company-profile">
        <div class="top-box">
          <h2>部分在孵企业</h2>
          <a href="###">查看更多</a>
        </div>
        <div class="bottom-box">
          <ul class="page-list-group">
            <li class="page-list">
              <span class="page-theme">网络安全宣传周</span>

              <a href="###"><img src="" alt="####"></a>

              <h4>2022清华大学网络安全宣传周系列活动奥术大师多</h4>
              <span class="event-date">2022年9月5日-2022年9月1日</span>
              <span class="organizer">清华大学</span>
            </li>
            <li class="page-list">
              <span class="page-theme">网络安全宣传周</span>

              <a href="###"><img src="" alt="####"></a>

              <h4>2022清华大学网络安全宣传周系列活动奥术大师多</h4>
              <span class="event-date">2022年9月5日-2022年9月1日</span>
              <span class="organizer">清华大学</span>
            </li>
            <li class="page-list">
              <span class="page-theme">网络安全宣传周</span>

              <a href="###"><img src="" alt="####"></a>

              <h4>2022清华大学网络安全宣传周系列活动奥术大师多</h4>
              <span class="event-date">2022年9月5日-2022年9月1日</span>
              <span class="organizer">清华大学</span>
            </li>
            <li class="page-list">
              <span class="page-theme">网络安全宣传周</span>

              <a href="###"><img src="" alt="####"></a>
              <h4>2022清华大学网络安全宣传周系列活动奥术大师多</h4>
              <span class="event-date">2022年9月5日-2022年9月1日</span>
              <span class="organizer">清华大学</span>
            </li>
          </ul>
        </div>
      </div>
</template>

<script>
export default {
name: "IncubationCompany",
  data() {
    return {};
  },
  methods: {},
  created() {},
  mounted() {},
};
</script>

<style lang="scss" scoped>
.company-profile{
  .top-box{
    position: relative;
    overflow: hidden;
    h2{
      height: 80px;
      font-size: 38px;
      font-weight: 700;
      color: #797979;
      text-align: center;
      line-height: 80px;
    }
    a{
      position: absolute;
      top: 32px;
      right: 0;
      font-size: 18px;
      font-weight: 400;
      color: #797979;
    }
  }
  li{
    float: left;
    width: 386px;
    margin-right: 25px;
    &:nth-child(4n){
      margin-right: 0;
    }
    span{
      display: block;
    }
  }
  .page-list{
    .page-theme{
      height: 50px;
      font-size: 14px;
      font-weight: 700;
      color: #797979;
      line-height: 50px;
    }
    a{
       display: block;
       height: 270px;
       opacity: 0.3;
       background: #000000;
    }
    h4{
        color: #797979;
        font-size: 20px;
        font-weight: 700;
        margin-bottom: 30px;
    }
    .event-data, .organizer{
        color: #797979;
        font-size: 16px;
        font-weight: 400;
    }
  }
}

.page-list-group {
  overflow: hidden;
}

</style>
