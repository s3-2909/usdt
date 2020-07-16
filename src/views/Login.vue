<template>
  <div>
    <nav-bar class="navBar-login" title left-text left-arrow @click-left="onClickLeft" />
  
  </div>
</template>

<script>
import { NavBar } from "vant";
export default {
  components: {
    NavBar
  },
  methods: {
    onClickLeft() {}
  }
};
</script>

<style lang="less">
.navBar-login {
  background: transparent !important;
  .van-icon {
    color: #fff;
    font-size: .24rem;
  }
  &:after {
    border: unset !important;
  }
}
</style>