<template>
  <div class="card">
    <h1>{{card_title}}</h1>
  </div>
</template>

<script>
export default {
  props: {
    card_title: String
  }
};
</script>

<style lang="scss" scoped>
.card {
  width: 50%;
  height: auto;
  background-color: white;
  box-shadow: 2px;
}
</style>
