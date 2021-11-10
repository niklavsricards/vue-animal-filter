<template>
  <a href="#" class="button">{{ item }}</a>
</template>

<script>
export default {
  name: "FilterButton",
  props: {
    item: String
  }
}
</script>

<style scoped>
  .button {
    margin: 5px;
    padding: 10px;
    color: white;
    background: #2c3e50;
    border: 1px solid black;
    border-radius: 5px;
    text-decoration: none;
  }

  .button:hover {
    opacity: 0.5;
  }
</style>