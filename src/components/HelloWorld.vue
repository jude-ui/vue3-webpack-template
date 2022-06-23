<template>
  <h2>{{ msg }}</h2> 
  <img
    src="~assets/logo_webpack.jpeg"
    alt="HEROPY" />
  <img
    src="~assets/vue.png"
    alt="vue" />
  <h3>VUE3 WEBPACK TEMPLATE</h3>
</template>

<script>
export default {
  props: {
    msg: {
      type: String,
      default: ''
    }
  }
}
</script>

<style scoped lang="scss">
  h2 {
    font-size: 22px;
    & ~ img {
      width: 120px;
    }
  }
</style>