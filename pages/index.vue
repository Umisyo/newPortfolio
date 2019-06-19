<template>
  <div class="container">
    <h1 class="name">
      <span>ク</span>スノキ <span>ソ</span>ウタ
    </h1>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
@import url('~/assets/style/common.scss');
$acsent_color: #E74C3C;

.name {
  position: relative;
  -webkit-writing-mode: vertical-rl;
  -moz-writing-mode: vertical-rl;
  -ms-writing-mode: tb-rl;
  -ms-writing-mode: vertical-rl;
  writing-mode: vertical-rl;
  box-sizing: border-box;
  margin: auto;
  width: 60px;
  font-size: 51px;
  line-height: 1.43;
  text-align: center;
  letter-spacing: 50px;
  display: inline-block;
  z-index: 1;
  font-weight: 100;

  span {
    color: $acsent_color;
  }
}
</style>
