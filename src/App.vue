<template>
  <div id="app">
    <router-view /> 
  </div>
</template>

<style lang="less">
#app {
  background-image: url('./assets/images/background.png');
  background-size: 100% 100%;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
  width: 100%;
  height: 100vh;
}
</style>
