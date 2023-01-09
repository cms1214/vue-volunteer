<template>
  <div id="app" ref="main">
    <MainHead/>
    <TitleText title="相关文件" subtitle="来看一看" />
  </div>
</template>

<script>
import TitleText from './components/TitleText'
import MainHead from './components/MainHead'

export default {
  name: 'App',
  components: {
    TitleText,
    MainHead
  }
}


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #FDF6F5;
  height: 3000px;
}
body{
  margin: 0;
}
a{
  text-decoration: none;
}



/* 组件 */
#head{
  position: sticky;
  top: 0px;
  left: 0px;
}
</style>
