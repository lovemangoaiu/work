<template>
  <header class="header">
    <div class="gradient">
      <div class="header-center">
        <div class="logo">
          <a href="###"><img src="./images/园区LOGO单独.png" alt="logo" /></a>
        </div>
        <nav class="nav-header">
          <ul class="nav-top">
            <li class="nav-item"><a href="###">首页</a></li>
            <li class="nav-item">
              <a href="###"> 园区概况 </a>
              <menu class="menu">
                <ul class="menu-list">
                  <li><a href="###">园区简介</a></li>
                  <li><a href="###">组织架构</a></li>
                  <li><a href="###">荣誉资质</a></li>
                  <li><a href="###">集团概况</a></li>
                  <li><a href="###">政企交流</a></li>
                  <li><a href="###">校企交流</a></li>
                  <li><a href="###">订阅关注</a></li>
                </ul>
              </menu>
            </li>
            <li class="nav-item">
              <a href="###">投资孵化</a>
              <menu class="menu">
                <ul class="menu-list">
                  <li><a href="###">中介合作机构</a></li>
                  <li><a href="###">部分毕业企业</a></li>
                  <li><a href="###">部分在孵企业</a></li>
                </ul>
              </menu>
            </li>
            <li class="nav-item">
              <a href="###">资源平台</a>
              <menu class="menu">
                <ul class="menu-list">
                  <li><a href="###">企业展厅简介</a></li>
                  <li><a href="###">大型会议、活动申请</a></li>
                  <li><a href="###">小型会议申请</a></li>
                  <li><a href="###">众创空间简介</a></li>
                  <li><a href="###">工位申请</a></li>
                  <li><a href="###">会议室申请</a></li>
                </ul>
              </menu>
            </li>
            <li class="nav-item">
              <a href="###">最新资讯</a>
              <menu class="menu">
                <ul class="menu-list">
                  <li><a href="###">园区动态</a></li>
                  <li><a href="###">集团新闻</a></li>
                  <li><a href="###">媒体报道</a></li>
                </ul>
              </menu>
            </li>
            <li class="nav-item">
              <a href="###">联系我们</a>
              <menu class="menu">
                <ul class="menu-list">
                  <li><a href="###">加入我们</a></li>
                  <li><a href="###">联系我们</a></li>
                </ul>
              </menu>
            </li>
            <li class="nav-item"><a href="###">0755-86534059</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "homeHeader",
  data() {
    return {};
  },
  methods: {},
  created() {},
  mounted() {},
};
</script>
<style lang="scss" scoped>
.header {
  height: 650px;
  background-image: url("./images/轮播图1.png");
  background-repeat: no-repeat;
  background-size: cover;
  .gradient {
    height: 120px;
    opacity: 0.8;
    background: linear-gradient(0deg, rgba(2, 133, 248, 0) 0%, #2774b8 100%);
    .header-center {
      width: 1920px;
      height: 120px;
      margin: 0 auto;
      .logo {
        float: left;
        width: 115px;
        height: 115px;
        margin-top: 30px;
        margin-left: 30px;
      }
      .nav-header {
        .nav-top {
          float: right;
          & > li {
            float: left;
            & > a {
              margin: 0 50px;
              height: 80px;
              font-size: 20px;
              font-weight: 700;
              color: #ffffff;
              line-height: 80px;
              text-shadow: 0.71px 0.71px 0px 1px #012753;
            }
            .menu {
              margin: 0 auto;
              padding: 0;
              .menu-list {
                background: #ffffff;
                width: 160px;
                margin: 0 auto;
                a {
                  display: block;
                  height: 40px;
                  font-size: 16px;
                  font-weight: 400;
                  text-align: center;
                  color: #0285f8;
                  line-height: 40px;
                  &:hover {
                    background: #0285f8;
                    color: #fff;
                  }
                }
              }
            }
          }
        }
      }
    }
  }
}
</style>
