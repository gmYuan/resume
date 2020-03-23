<template>
  <!-- 技能 -->
  <div class="part_wrap">
    <div>
      <h2 class="header">专业技能</h2>
    </div>

    <ul class="skills">
      <li class="column">掌握HTML(5)和常用CSS(3)相关知识，能够较好地还原设计稿。</li>

      <li class="column">
        JS基础良好，理解其重要概念如:
        <button class="import_txt">原型</button>，
        <button class="import_txt">闭包</button>，
        <button class="import_txt">this</button>，
        <button class="import_txt">事件循环</button>
        等。
      </li>

      <li class="column">
        掌握ES6的相关知识，并能运用在实际项目中，如:
        <button class="import_txt">解构赋值</button>，
        <button class="import_txt">箭头函数</button>，
        <button class="import_txt">Promise</button>
        等。
      </li>

      <li class="column">
        熟悉Vue框架及相关流行库的使用，理解重要概念如：
        <button class="import_txt">生命周期</button>，
        <button class="import_txt">组件通信</button>，
        <button class="import_txt">响应式原理</button>
        等。
      </li>

      <li class="column">能够编写简单的 Vue 基础组件，以及完成相应的单元测试。</li>

      <li class="column">
        了解
        <button class="import_txt">HTTP协议</button>，
        了解 常见的前端性能优化策略，如
        <button class="import_txt">防抖/节流</button> 等。
      </li>

      <li class="column">
        掌握常用的
        <button class="import_txt">Git</button> 命令 ，
        了解 前端工程化相关的工具，如 webpack 等。
      </li>

      <li class="column">
        追求风格优雅，整洁的代码。通过
        使用有意义的变量名以及意义明确的代码，提高代码的
        <button class="import_txt">可读性</button> 。
      </li>

      <li class="column">
        注重基础知识的积累，能够手写 call/apply等函数的实现，
        有写 
        <a href="http://ygming.me/my_learn/" target="_blank;">技术博客</a> 的习惯。
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "skills"
};
</script>


<style scoped>
.skills {
  padding-top: 15px;
  padding-left: 15px;
}
.column {
  padding: 3px 0;
  margin-left: 20px;
  list-style: circle;
}

.import_txt {
  padding: 0 2px;
  color: #2196f3;
  background: #eeeeee;
  border: 1px solid #cfd8dc;
  border-radius: 2px;
}

.column a {
  color: #E91E63;
  text-decoration: underline;
}

</style>
