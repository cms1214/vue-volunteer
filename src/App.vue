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

/* 滚动条 */
/* body{
  overflow-y: overlay;
}
body::-webkit-scrollbar {
  width: 20px;
}
body::-webkit-scrollbar-thumb {
  border-radius: 10px;
  box-shadow: inset 0 0 5px rgba(0,0,0,0.2);
  background: rgba(0,0,0,0.2);
}
body::-webkit-scrollbar-track {
  background: rgba(0, 0, 0, 0);
} */


/* 组件 */
#head{
  position: sticky;
  top: 0px;
  left: 0px;
}
</style>
