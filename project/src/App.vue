<template>
  <div id="app">
    <Contents/>
  </div>
</template>

<script>
import Contents from './components/index'


export default {
  name: 'App',
  components: {
    Contents
  }
}
</script>

<style>
#app {

}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  outline: none !important;
}
body {
  background-color: #f5f2f2;
}
.menu {
  z-index: 10;
  background-color: #80bb35;
}
.content {
  width: 80%;
  margin: auto;
  margin-top: 20px;
}
p {
  margin: 0;
  padding: 0;
}
</style>
