<template>
  <div class="cards">
    <Card v-for="item in cardItems" :item="item" :key="item.id"/>
  </div>
</template>

<script>
import Card from "@/components/Card";

export default {
  name: "Cards",
  components: {
    Card
  },
  data: () => ({
    cardItems: [
      {
        "id": 1,
        "breed": "dog",
        "name": "Rex"
      },
      {
        "id": 2,
        "breed": "cat",
        "name": "Mike"
      }
    ]
  })
}
</script>

<style scoped>

</style>