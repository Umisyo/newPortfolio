<template>
  <h1 class="name">
    <span>ク</span>スノキ
    <span>ソ</span>ウタ
  </h1>
</template>

<script></script>

<style lang="scss" scoped>
$acsent_color: #e74c3c;

.name {
  position: relative;
  -webkit-writing-mode: vertical-rl;
  -moz-writing-mode: vertical-rl;
  -ms-writing-mode: tb-rl;
  -ms-writing-mode: vertical-rl;
  writing-mode: vertical-rl;
  box-sizing: border-box;
  width: 60px;
  margin-top: 10%;
  margin-right: auto;
  margin-left: 50%;
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
