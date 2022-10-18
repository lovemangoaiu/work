<template>
  <div class="resource-plat">
    <div class="top-box">
      <h2>资源平台</h2>
    </div>
    <div class="bottom-box">
      <ul class="graphic">
        <li class="item-box">
          <a href="###" class="img"
            ><img src="./images/中地大楼.png" alt="中地大楼"
          /></a>
          <header class="text-layer">
            <h3>中地大楼</h3>
            <em>数字创意产业聚焦区</em>
            <em><a href="###">了解更多</a></em>
          </header>
        </li>
        <li class="item-box">
          <a href="###" class="img"
            ><img src="./images/空间信息企业展厅.png" alt="空间信息企业展厅"
          /></a>
          <header class="text-layer">
            <h3>空间信息企业展厅</h3>
            <em>一站式企业服务</em>
            <em><a href="###">了解更多</a></em>
          </header>
        </li>
        <li class="item-box">
          <a href="###" class="img"
            ><img src="./images/空间信息众创空间.png" alt="空间信息众创空间"
          /></a>
          <header class="text-layer">
            <h3>空间信息众创空间</h3>
            <em>创新型孵化空间</em>
            <em><a href="###">了解更多</a></em>
          </header>
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "ResourcePlat",
  data() {
    return {};
  },
  methods: {},
  created() {},
  mounted() {},
};
</script>
<style lang="scss" scoped>
.resource-plat {
  width: 1620px;
  margin: 30px auto;
  .top-box {
    h2 {
      height: 80px;
      font-size: 38px;
      text-align: center;
      line-height: 80px;
    }
  }
  .bottom-box {
    li {
      position: relative;
      float: left;
      margin-right: 30px;

      &:nth-child(3n) {
        margin-right: 0;
      }

      a {
        width: 520px;
        height: 725px;
      }

      .text-layer {
        position: absolute;
        top: 0;
        height: 230px;
        width: 520px;
        background-color: rgba(0, 0, 0, 0.3);

        h3 {
          height: 55px;
          font-size: 34px;
          font-weight: 700;
          text-align: center;
          color: #fff;
          line-height: 55px;
        }

        em {
          display: block;
          font-size: 20px;
          font-weight: 700;
          text-align: center;
          color: #ffffff;
          line-height: 30px;

          a {
            display: block;
            margin: 0 auto;
            height: 55px;
            width: 80px;
            font-size: 18px;
            font-weight: 400;
            text-align: center;
            color: #ffffff;
            line-height: 55px;
          }
        }
      }
    }
  }
}
</style>
