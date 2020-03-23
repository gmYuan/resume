<template>
  <!-- 工作经历部分 -->
  <div class="part_wrap">
    <div>
      <h2 class="header">工作经历</h2>
    </div>

    <ul class="company">
      <!-- <li class="column">
        <i class="icon"></i>
        2017.04 - 2018.02：任职于
        <span class="txt">无锡梵天信息股份有限公司，测试工程师</span>
        ，主要负责 手游测试。
      </li>-->

       <li class="column">
        <i class="icon"></i>
        2019.03 - 2020.03：任职于
        <span class="txt">上海铭诺网络科技有限公司，Web前端工程师</span>
        ，主要负责 反洗钱、樊登读书等项目的 前端工作。
      </li>

      <li class="column">
        <i class="icon"></i>
        2018.02 - 2019.03：任职于
        <span class="txt">上海墨灿网络科技有限公司，测试工程师</span>
        ，主要负责 FloryDay项目测试。
      </li>
     
    </ul>
  </div>
</template>

<script>
export default {
  name: "workCompany"
};
</script>


<style scoped>
.company {
  padding-top: 15px;
  padding-left: 15px;
}
.column {
  padding: 6px 0px;
}

.icon {
  display: inline-block;
  width: 26px;
  height: 26px;
  vertical-align: sub;
  background: url("../assets/company.svg");
  background-size: cover;
}

.txt {
  padding-bottom: 2px;
  border-bottom: 1px solid #000;
}
</style>
