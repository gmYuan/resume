<template>
  <!-- 个人信息部分 -->
  <div class="part_wrap">
    <!-- <div>
      <h2 class="header">基本信息</h2>
    </div>-->

    <!-- <ul class="info">
      <li class="column">
        <div>
          <span>姓&emsp;&emsp;名:</span>
          <span class="txt">袁广明</span>
        </div>
        <div></div>
        <div>
          <span>联系方式:</span>
          <span class="txt">15505253353</span>
        </div>
      </li>
      <li class="column second">
        <div>
          <span>应聘职位:</span>
          <span class="txt">前端工程师</span>
        </div>
        <div></div>
        <div>
          <span>邮&emsp;&emsp;箱:</span>
          <span class="txt">ygm121351@gmail.com</span>
        </div>
      </li>

      <li class="column pic-wrap">
        <img src="../assets/myself2.jpg" alt="个人" />
      </li>
    </ul>-->

    <el-container>
      <el-header>
        <h2 class="header">基本信息</h2>
      </el-header>

      <el-container>
        <el-main>
          <el-row type="flex" justify="space-between" class="fp">
            <el-col :span="12" :xs="24" class="pad5">
              <span>姓&emsp;&emsp;名:</span>
              <span class="txt">袁广明</span>
            </el-col>
            <el-col :span="12" :xs="24" class="pad5">
              <span>应聘职位:</span>
              <span class="txt">前端工程师</span>
            </el-col>
          </el-row>

          <el-row type="flex" justify="space-between"  class="fp">
            <el-col :span="12" :xs="24" class="pad5">
              <span>出生年月:</span>
              <span class="txt">1995.01</span>
            </el-col>
            <el-col :span="12" :xs="24" class="pad5">
              <span>学&emsp;&emsp;历:</span>
              <span class="txt">本科</span>
            </el-col>
          </el-row>

          <el-row type="flex" justify="space-between"  class="fp">
            <el-col :span="12" :xs="24" class="pad5">
              <span>联系方式:</span>
              <span class="txt">19962321623</span>
            </el-col>
            <el-col :span="12" :xs="24" class="pad5">
              <span>邮&emsp;&emsp;箱:</span>
              <span class="txt">ygm121351@163.com</span>
            </el-col>
          </el-row>
        </el-main>

        <el-aside class="hidden-xs-only picSelf" width="100px">
          <el-row  class="fp">
            <el-col :span="24">
              <div class="i-self"></div>
            </el-col>
          </el-row>
        </el-aside>

      </el-container>
    </el-container>

  </div>
</template>

<script>
export default {
  name: "baseInfo"
};
</script>


<style scoped>
.txt {
  padding-left: 5px;
}

.i-self {
  width: 80px;
  height: 100px;
  border-radius: 2px;
  background-image: url("../assets/myself.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

.picSelf {
  margin-top: 12px;
}
</style>
