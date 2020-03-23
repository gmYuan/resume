<template>
  <div id="app">
    <main class="main">
      <baseInfo></baseInfo>
      <workCompany></workCompany>
      <skills></skills>
      <projects></projects>
      <other></other>

    </main>
  </div>
</template>

<script>

import baseInfo from './components/baseInfo'
import workCompany from './components/workCompany'
import skills from './components/skills'
import projects from './components/projects'
import other from './components/other'


export default {
  name: 'App',
  components: {
    baseInfo,
    workCompany,
    skills,
    projects,
    other
  }
}
</script>

<style lang='scss'>
.main {
  width: 80vw;
  margin: 0 auto;
  box-shadow: 0 0 0 0.75pt #d1d1d1, 0 0 3pt 0.75pt #ccc;
}

</style>
