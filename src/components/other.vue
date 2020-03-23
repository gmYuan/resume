<template>
  <!-- 工作经历部分 -->
  <div class="other">

    <div class="part_wrap">
      <h2 class="header">其他项目</h2>
    </div>

    <ul class="other_content">
      在空余时间，自行学习了多个小项目。例如
      <li class="column">
        <a href="https://github.com/gmYuan/cNode">
          Vue实现cnode社区
        </a>
      </li>
      <li class="column">
        <a href="https://github.com/gmYuan/Browser_Navigation">
          小巧的页面导航
        </a>
      </li>
      <li class="column link">
        <span>更多内容，见: </span>
        <i class="github_icon"></i>
        <a href="https://github.com/gmYuan">Github</a>
      </li>
    
    </ul>

    
  </div>
</template>

<script>
export default {
  name: 'other'

}
</script>


<style scoped>

.other_content {
  padding-top: 15px;
  padding-left: 30px;
}

.column {
  padding: 3px 0;
  margin-left: 20px;
  list-style: none;
}

.column a {
  color: #E91E63;
  text-decoration: underline;
}

.github_icon::before {
  content: '';
  display: inline-block;
  vertical-align: bottom;
  width: 30px;
  height: 30px;
  background: url('../assets/GitHub.svg') no-repeat;
  background-size: 90%;
} 

.link {
  margin-bottom: 5px;
}
</style>
