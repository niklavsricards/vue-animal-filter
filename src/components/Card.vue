<template>
  <div>
    <h1>{{ item.name }}</h1>
    <p>{{ item.breed }}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    item: Object
  },
}
</script>

<style scoped>
  div {
    height: 250px;
    width: 250px;
    background: darkgray;
    display: inline-block;
    margin: 100px 20px 20px;
  }
</style>