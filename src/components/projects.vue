<template>
  <!-- 技能 -->
  <div class="part_wrap">
    <div>
      <h2 class="header">项目经验</h2>
    </div>

    <ul class="projects">
      <!-- 第1个项目 -->
      <li class="project">
        <div class="title">
          <h3>樊登读书APP</h3>
        </div>
        <!-- <div class="pro_pic">
          <img src="../assets/cNode.jpg" alt="作品1">
        </div>-->
        <div class="desc">
          <p>
            该项目为 混合开发的移动端项目， 负责整个项目的主要页面 样式和功能实现，包括 首页、课程列表页、
            课程详情页、数据统计页、个人中心页等。
            在开发过程中，熟悉了Vue的一些高级特性使用，如 Solt、Mixins等，并封装了一些 公用组件。
          </p>
          <ul class="skill-stack">
            <li>使用 Vue 全家桶，配合Vant UI库，自行编写基础组件进行 项目开发。</li>
            <li>深入熟悉了一些 Vue特性，如 响应式原理、$nextTick等。</li>
          </ul>
        </div>

        <div class="icons">
          <div class="icon_wrap">
            <span>
              <b>JS</b>
            </span>
            <span class="vue_icon"></span>
            <span class="sass_icon"></span>
            <span class="webpack_icon"></span>
          </div>

          <!-- <div class="link_wrap">
             <a class="link_txt" href="https://github.com/gmYuan/cNode" target="_blank">
               项目地址
             </a>
             <a class="link_txt" href=" http://ygming.me/cNode/dist/index.html" target="_blank">
               效果预览
             </a>
          </div>-->
        </div>
      </li>

      <!-- 第2个项目 -->
      <li class="project">
        <div class="title">
          <h3>反洗钱管理后台</h3>
        </div>
        <!-- <div class="pro_pic">
          <img src="../assets/163.png" alt="作品2" class="work2">
        </div>-->
        <div class="desc">
          <p>
            该项目由Angular框架转为Vue重构，负责这个项目的样式和功能逻辑重写。
            项目中使用到了 element-ui 和 vue-element-admin 库，实现了常见的后台功能。
            在实现功能的过程中，对原有封装组件结合项目需求，进行了阅读修改，如分页组件等。
          </p>
          <!-- <p>
            项目中的重难点记录，见
            <a
              class="link_content"
              href="https://github.com/gmYuan/Work-Code/tree/master/01%20%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%E7%A7%BB%E5%8A%A8%E7%AB%AF"
            >项目难点记录</a>
          </p>
          <p>技术栈： jQuery + SASS + LeanCloud + 七牛</p>-->
          <ul class="skill-stack">
            <li>使用 Vue 全家桶，配合vue-element-admin库，编写组件进行 项目开发。</li>
            <li>在第三方库所提供的组件未能满足业务的需求下，完善了组件功能，如 分页组件等。</li>
          </ul>
        </div>

        <div class="icons">
          <div class="icon_wrap">
            <span>
              <b>JS</b>
            </span>
            <span class="vue_icon"></span>
            <span class="sass_icon"></span>
            <span class="admin_icon"></span>
          </div>

          <!-- <div class="link_wrap">
            <a class="link_txt" href="https://github.com/gmYuan/163-music/" target="_blank">项目地址</a>
          </div> -->
        </div>
      </li>

      <!-- 第3个项目 -->
      <li class="project">
        <div class="title">
          <h3>个人Vue UI组件库</h3>
        </div>
        <!-- <div class="pro_pic">
          <img src="../assets/pikaqiu.jpg" alt="作品3" class="work3" />
        </div> -->
        <div class="desc">
          <p>该项目是个人项目，通过Vue来封装一个 个人的Vue UI库，实现了Button、网格、
            Toast、Tabs、popover等基础组件，通过这个简单轮子，进一步熟悉Vue的高级使用，从而
            为深入学习Vue内容打下基础。
          </p>
          <ul class="skill-stack">
            <li>使用 Vue，参考主流UI库的使用方法， 独立完成了一些简单功能组件。</li>
            <li>引入了单元测试，通过Karma、Mocha等测试库 编写单元测试。</li>
          </ul>
        </div>

        <div class="icons">
          <div class="icon_wrap">
            <span>
              <b>JS</b>
            </span>
            <span class="vue_icon"></span>
            <span class="mocha_icon"></span>
          </div>

          <div class="link_wrap">
            <a class="link_txt" href="https://github.com/gmYuan/Vea" target="_blank">项目地址</a>
            
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "projects"
};
</script>


<style scoped>
.projects {
  padding-top: 15px;
  padding-left: 15px;
  padding-bottom: 10px;
}

.project {
  padding: 0 10px;
  margin-bottom: 30px;
  background: white;
  border: 1px solid #edeeee;
  border-radius: 3px;
  transition: all 0.5s ease-in-out;
  box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 30px,
    rgba(0, 0, 0, 0.23) 0px 6px 10px;
}

.project:last-child {
  margin-bottom: 0px;
}

.title {
  padding: 10px 0;
  text-align: center;
  color: rgb(78, 78, 78);
  font-size: 14px;
}

.pro_pic {
  padding: 10px 0;
}

.pro_pic img {
  display: block;
  height: 190px;
  width: 80%;
}
.desc {
  padding: 10px 0;
  font-size: 14px;
  line-height: 1.8;
}

.icons {
  margin-top: 3px;
  padding-left: 5px;
  padding-top: 3px;
  border-top: 1px solid #eeefef;

  display: flex;
  justify-content: space-between;
  align-items: center;
}

.icon_wrap {
  display: flex;
  flex-basis: 30%;
  justify-content: space-between;

  font-size: 1.3rem;
  width: 40px;
  height: 40px;
  text-align: center;
  line-height: 40px;
  color: #a5a7aa;
}

.vue_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/vue.svg") no-repeat;
  background-size: 90%;
}

.sass_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/SASS.svg") no-repeat;
  background-size: 90%;
}

.webpack_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/Webpack.svg") no-repeat;
  background-size: 90%;
}

.jquery_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/jQuery.svg") no-repeat;
  background-size: 90%;
}
.admin_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 88px;
  height: 30px;
  background: url("../assets/admin.svg") no-repeat;
  background-size: cover;
}

.mocha_icon::before {
  content: "";
  display: inline-block;
  vertical-align: sub;
  width: 25px;
  height: 25px;
  background: url("../assets/mocha.svg") no-repeat;
  background-size: 90%;
}
.prims_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/prims.svg") no-repeat;
  background-size: 90%;
}
.mobile_icon::before {
  content: "";
  display: inline-block;
  vertical-align: text-top;
  width: 30px;
  height: 30px;
  background: url("../assets/mobile.svg") no-repeat;
  background-size: 90%;
}

.link_wrap {
  margin-right: 12px;
}

.link_txt {
  display: inline-block;
  padding: 3px;

  border-radius: 3px;
  background: white;
  border: 1px solid #d5d6d8;

  color: #a5a7aa;
  font-size: 14px;
  font-weight: bold;
}
.link_txt:hover {
  background: #eee;
}

.link_content {
  color: #e91e63;
}

/* 第2个作品截图样式 */
.pro_pic .work2 {
  display: block;
  height: 190px;
  width: 50%;
}

/* 第3个作品截图样式 */
.pro_pic .work3 {
  display: block;
  height: 150px;
  width: 50%;
}

.skill-stack li {
  padding: 5px 0;
  list-style: inside;
  color: #333;
}
</style>
