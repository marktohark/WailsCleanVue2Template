<template>
  <div class="result">{{result}}</div>
</template>

<script>
export default {
  name: "Result",
  props: {
    result: {
      type: String,
      default: () => '',
    }
  },
}
</script>

<style scoped>
  .result {
    height: 20px;
    line-height: 20px;
    margin: 1.5rem auto;
  }
</style>