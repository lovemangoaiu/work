<template>
<div class="park-card">
        <div class="text-desc">
          <h2>做行业内最顶尖的产业园</h2>
          <p>
            深圳市空间信息信息技术产业园作为中地数码集团产业孵化载体之一，是面向深圳市地理信息技术产业链及上下游配套企业开展孵化及技术服务工作的重要科技企业孵化基地。<br>
            产业园积极探索解决高校、科研院所与高新技术产业中间地带问题，形成了“孵化+增值”的产学研一体化、“信创+数字经济”的双引擎服务模式，推动创新链、产业链双向升级,为入驻企业提供全方位、全过程的一站式服务，着力打造具有广泛影响力的创新型科技企业专业孵化园区。<br>
            经过十多年的发展，园区现已成为地理空间信息技术产业行业领域的专业孵化园区，带动了空间信息技术的转型升级，有利的推动了产业辐射。
          </p>
        </div>
      </div>
</template>
<script>
export default {
  name: "ParkCard",
  data() {
    return {};
  },
  methods: {},
  created() {},
  mounted() {},
};
</script>
<style lang="scss" scoped>
.park-card{
    width: 1620px;
    height: 911px;
    background: url("/demo/img/做行业内最顶尖的产业园\ .png");
    .text-desc{
      margin-left: 40px; 
    }
    h2{
      font-size: 60px;
      font-weight: 400;
      color: #ffffff;
      line-height: 160px;
    }
    p{
      width: 1405px;
      font-size: 19px;
      font-weight: 400;
      color: #ffffff;
      line-height: 36px;
      letter-spacing: 1.52px;
    }
}
</style>
